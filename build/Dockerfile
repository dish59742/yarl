FROM ubuntu:18.04
RUN apt-get update && \
    apt-get install --no-install-recommends -y gcc python3 python3-pip python3-dev && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

RUN python3 --version
