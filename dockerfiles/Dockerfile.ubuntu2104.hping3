FROM ubuntu:21.04    
LABEL org.opencontainers.image.authors="githubfoam"

RUN apt-get update && apt-get install -y --no-install-recommends \
    wget \
    libpcap-dev

RUN wget http://www.hping.org/hping3-20051105.tar.gz && \
    tar xzvf  hping3-20051105.tar.gz && \
    cd hping3-* && \
    cat bytesex.h && \
    wget https://raw.githubusercontent.com/galkan/tools/master/others/patches/hping-rand-pattern && \
    pwd

RUN wget https://raw.githubusercontent.com/galkan/tools/master/others/patches/hping-rand-pattern && \
    pwd

# RUN stat /usr/include/pcap-bpf.h && \
#     ln -s /usr/include/pcap-bpf.h /usr/include/net/bpf.h

#testing
# RUN hping3 -v

