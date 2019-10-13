FROM alpine:3.10
LABEL maintainer="Lukas f. Paluch <fluktuid@gmail.com>"

RUN apk update
RUN apk add texlive-full=20190410-r1
RUN apk add ca-certificates=20190108-r0

VOLUME ["/source"]
WORKDIR /source
CMD ["bash"]
