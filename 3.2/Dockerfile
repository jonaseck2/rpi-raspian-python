FROM resin/rpi-raspbian:wheezy

# Install dependencies
RUN apt-get purge -y python.* \
 && apt-get update && apt-get install -y \
    python3 \
    python3-dev \
    python3-pip \
    gcc \
    make \
    --no-install-recommends && \
    rm -rf /var/lib/apt/lists/* \
 && cd /usr/bin \
 && rm -f pydoc && ln -s pydoc3 pydoc \
 && rm -f python && ln -s python3 python \
 && rm -f pip && ln -s pip-3.2 pip
