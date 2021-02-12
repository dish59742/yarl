FROM ubuntu:18.04
RUN apt-get update && apt-get install -y autoconf automake curl wget cmake git libtool make build-essential software-properties-common \
    && add-apt-repository ppa:deadsnakes/ppa \
    && apt-get install -y python3 python3-pip python3-dev \
    && git clone --depth=1 https://github.com/aio-libs/yarl.git /yarl \
    && cd /yarl \
    && which python3 \
    && pip3 --version

RUN pwd

RUN uname -m
