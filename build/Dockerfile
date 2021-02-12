FROM ubuntu:18.04
RUN apt-get update && apt-get install -y autoconf automake curl wget cmake git libtool make build-essential software-properties-common \
    && add-apt-repository ppa:deadsnakes/ppa \
    && git clone --depth=1 https://github.com/aio-libs/yarl.git /yarl \
    && cd /yarl
    
RUN apt-get install -y python3.8

RUN pwd

RUN uname -m
