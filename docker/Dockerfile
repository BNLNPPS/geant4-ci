FROM debian:12.13

RUN apt-get update && apt-get install -y \
    build-essential \
    cmake \
    git \
    qt6-base-dev \
    qt6-tools-dev \
    libhepmc3-dev \
    libxerces-c-dev \
    libxerces-c3.2 \
    libxmu-dev \
    libexpat1-dev \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

