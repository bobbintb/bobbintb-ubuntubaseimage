FROM ubuntu:jammy
ENV DEBIAN_FRONTEND noninteractive
RUN apt autoremove && apt autoclean -y
RUN apt update && apt-get -y install git wget mc aptitude nano sudo curl software-properties-common build-essential apt-utils && apt clean
