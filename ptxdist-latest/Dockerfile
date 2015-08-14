FROM doomhammer/ptxdist-base
MAINTAINER Piotr Gaczkowski <DoomHammerNG@gmail.com>

RUN cd /usr/src/ptxdist && \
    ./autogen.sh && \
    ./configure && \
    make && \
    make install && \
    rm -rf /usr/src

ENTRYPOINT [ "/usr/local/bin/ptxdist" ]
