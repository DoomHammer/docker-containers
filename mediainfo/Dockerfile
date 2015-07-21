FROM debian
MAINTAINER Piotr Gaczkowski <DoomHammerNG@gmail.com>

RUN apt-get update && \
    apt-get install -qqy \
    mediainfo && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "/usr/bin/mediainfo" ]
