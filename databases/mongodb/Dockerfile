from alpine:3.9
LABEL maintainer="Lukas f. Paluch <fluktuid@gmail.com>"
RUN apk add --no-cache mongodb=4.0.5-r0

volume /data/db
EXPOSE 27017 27017

COPY run.sh /root
RUN ["chmod","+x","/root/run.sh"]
ENTRYPOINT ["/root/run.sh"]
CMD ["mongod","--bind_ip","0.0.0.0"]
