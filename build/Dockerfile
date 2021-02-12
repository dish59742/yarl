FROM ubuntu:18.04
RUN apt-get update && apt-get install -y autoconf automake curl wget cmake git libtool make python3 python3-dev \
    && git clone --depth=1 https://github.com/aio-libs/yarl.git /yarl \
    && cd /yarl \
    && python3 setup.py bdist_wheel

RUN ls

RUN pwd

RUN uname -m
