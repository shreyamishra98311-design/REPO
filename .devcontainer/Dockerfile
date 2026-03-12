# Use Debian 12 (Bookworm) as the base
FROM debian:12

# Install common tools
RUN apt-get update && apt-get install -y \
    build-essential \
    curl \
    git \
    vim \
    && rm -rf /var/lib/apt/lists/*
