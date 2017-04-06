FROM alpine:3.3
MAINTAINER Erik Johansson <erik.johansson89@gmail.com>
LABEL maintainer "Erik Johansson <erik.johansson89@gmail.com>"

# ENV NMAP_VERSION 7.01-r1

RUN apk add --update --no-cache nmap  # ==${NMAP_VERSION}

VOLUME ["/data"]

ENTRYPOINT ["/usr/bin/nmap"]
CMD ["--help"]