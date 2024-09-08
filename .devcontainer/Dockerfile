FROM ubuntu:oracular-20240811.1

RUN apt-get update && \
    apt install -y \
        gcc \
        make \
        git \
        tzdata \
        ccls \
        && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

ENV TZ=Asia/Tokyo

