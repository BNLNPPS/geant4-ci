FROM debian:12.13

RUN apt-get update && apt-get install -y \
    qt6-base-dev \
    qt6-tools-dev \
    libhepmc3-dev \
    libxmu-dev \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

