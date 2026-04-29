# Use the official Node.js image (Debian-based for better tool support)
FROM node:22

# Install git so you can clone the repo
RUN apt-get update && apt-get install -y git

# Set a default working directory
WORKDIR /app

# Keeps the container running and drops you into a bash shell by default
CMD ["/bin/bash"]