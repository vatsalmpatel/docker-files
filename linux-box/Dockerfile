# Use the latest Ubuntu base image
FROM ubuntu:latest

# Set the working directory inside the container
WORKDIR /home/user

# Avoid prompts from apt during build
ENV DEBIAN_FRONTEND=noninteractive

# Update the system and install some basic "must-have" tools
RUN apt-get update && apt-get install -y \
    curl \
    vim \
    git \
    wget \
    build-essential \
    sudo \
    && rm -rf /var/lib/apt/lists/*

# Set the default command to bash so you have an interactive shell
CMD ["/bin/bash"]