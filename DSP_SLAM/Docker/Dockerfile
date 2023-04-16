# Use this for v1.0
# FROM ubuntu:20.04 

# Use this for v2.0
FROM nvidia/cuda:11.3.0-base-ubuntu20.04


# Install a GUI App for testing X11 forwarding
RUN apt-get update && \
    apt-get install -y software-properties-common && \
    add-apt-repository -y ppa:lucioc/sayonara
    # apt-get update && \
    # apt-get install -y sayonara

RUN apt-get update && \
    #-> Install general usage dependencies
    echo "Installing general usage dependencies ..." && \
    apt-get install -y \
    git \
    sudo \
    wget \
    cmake 
    
# RUN echo "Installing gedit ..." && \
#     apt-get install -y \
#     gedit 
    
RUN apt-get install -y  tar \
    libx11-dev \
    xorg-dev \
    libssl-dev \
    build-essential \ 
    libusb-1.0-0-dev \
    libglu1-mesa-dev \
    curl

RUN git clone --recursive https://github.com/JingwenWang95/DSP-SLAM.git
