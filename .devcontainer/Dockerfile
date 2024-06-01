# Use an official GCC runtime as a parent image
FROM gcc:latest

# Set the working directory in the container
WORKDIR /workspace

# Install any additional packages if needed
RUN apt-get update && apt-get install -y \
    cmake \
    make \
    gdb \
    && rm -rf /var/lib/apt/lists/*
