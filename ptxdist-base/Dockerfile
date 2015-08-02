FROM debian
MAINTAINER Piotr Gaczkowski <DoomHammerNG@gmail.com>

RUN apt-get update && \
    apt-get install -qqy \
    automake \
    bison \
    bzip2 \
    fakeroot \
    file \
    flex \
    gawk \
    gcc \
    g++ \
    gettext \
    git \
    libncurses-dev \
    make \
    patch \
    python-dev \
    texinfo \
    wget && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* && \
    mkdir -p /usr/src && \
    cd /usr/src && \
    git clone git://git.pengutronix.de/git/ptxdist.git
