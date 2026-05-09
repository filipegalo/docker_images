FROM --platform=linux/amd64 ubuntu:22.04

RUN apt-get update && apt-get install -y --no-install-recommends \
    git-crypt \
    rsync \
    curl \
    wget \
    openssh-client \
    ca-certificates \
    nodejs \
  && rm -rf /var/lib/apt/lists/*
