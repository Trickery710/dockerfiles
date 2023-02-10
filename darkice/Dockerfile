#
# Dockerfile for darkice
#

FROM debian:11
MAINTAINER EasyPi Software Foundation

RUN set -xe \
 && apt update -y \
 && apt install -y darkice \
 && rm -rf /var/lib/apt/lists/*

CMD ["darkice", "-c", "/etc/darkice/darkice.cfg"]
