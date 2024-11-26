FROM ubuntu:22.04

RUN apt-get update && apt-get install -y --no-install-recommends \
  ninja-build \
  build-essential \
  git \
  g++ \
  cmake \
  bison flex \
  libboost-all-dev \
  libevent-dev \
  libdouble-conversion-dev \
  libgoogle-glog-dev \
  libgflags-dev \
  libiberty-dev \
  liblz4-dev \
  liblzma-dev \
  libbz2-dev \
  libsnappy-dev \
  make \
  zlib1g-dev \
  binutils-dev \
  libjemalloc-dev \
  libssl-dev \
  pkg-config \
  libunwind-dev \
  libelf-dev \
  libdwarf-dev \
  libsodium-dev \
  libaio-dev \
  libnuma-dev \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/\* /tmp/\* /var/tmp/\*
