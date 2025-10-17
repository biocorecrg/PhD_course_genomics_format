FROM ubuntu:24.04

RUN apt update && apt install -y \
    curl \
    wget \
    awk \
    perl \
    ncbi-blast+ \
    git \
    samtools \
    build-essential \
    software-properties-common \
    lsb-release \
    gnupg2 \
    ca-certificates \
    && rm -rf /var/lib/apt/lists/*
