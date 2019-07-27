FROM ubuntu:12.04

SHELL ["/bin/bash", "-c"]
RUN apt-get clean \
    && apt-get update \
    && apt-get install -y qemu qemu-kvm-extras \
    && apt-get install -y gcc-arm-linux-gnueabi libc6-armel-armhf-cross \
    && apt-get install -y vim