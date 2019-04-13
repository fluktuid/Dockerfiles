FROM docker:18-git
LABEL maintainer="Lukas f. Paluch <fluktuid@gmail.com>"

RUN apk add gradle=4.10.3-r0

ENV JAVA_HOME=/opt/java
ENV PATH="$PATH:$JAVA_HOME/bin"

ENTRYPOINT ["/bin/sh"]
