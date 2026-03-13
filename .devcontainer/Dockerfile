FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends curl ca-certificates \
    && curl -fsSL https://deb.nodesource.com/setup_20.x | bash - \
    && apt-get -y install --no-install-recommends nodejs \
    && apt-get clean && rm -rf /var/lib/apt/lists/*

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
        libglib2.0-0 \
        libnss3 \
        libnspr4 \
        libatk1.0-0 \
        libatk-bridge2.0-0 \
        libcups2 \
        libdrm2 \
        libdbus-1-3 \
        libxcb1 \
        libxkbcommon0 \
        libatspi2.0-0 \
        libx11-6 \
        libxcomposite1 \
        libxdamage1 \
        libxext6 \
        libxfixes3 \
        libxrandr2 \
        libgbm1 \
        libpango-1.0-0 \
        libcairo2 \
        libasound2t64 \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
