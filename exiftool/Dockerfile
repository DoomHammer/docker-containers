FROM debian
MAINTAINER Piotr Gaczkowski <DoomHammerNG@gmail.com>

RUN apt-get update && \
    apt-get install -qqy \
    libimage-exiftool-perl && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "/usr/bin/exiftool" ]
