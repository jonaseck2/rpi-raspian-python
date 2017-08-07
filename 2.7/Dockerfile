FROM resin/rpi-raspbian:wheezy

# Install dependencies
RUN apt-get update && apt-get install -y \
    python2.7 \
    python2.7-dev \
    python-pip \
    gcc \
    make \
    --no-install-recommends && \
    rm -rf /var/lib/apt/lists/*
