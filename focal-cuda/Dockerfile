FROM nvidia/cuda:11.4.2-cudnn8-runtime-ubuntu20.04
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update && apt-get -y install git wget mc aptitude nano sudo curl software-properties-common build-essential apt-utils && apt-get clean && rm -rf /var/lib/apt/lists/*
