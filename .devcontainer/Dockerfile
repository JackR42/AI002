# Use the base image for development
FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

# Install any dependencies you need here
RUN apt-get update && apt-get install -y \
    curl \
    git \
    build-essential

# Set the working directory
WORKDIR /workspace

# Copy all files from the local file system to the container
COPY . /workspace

# Run any commands you need to set up your environment
# For example, to install Node.js dependencies you could include:
# RUN curl -sL https://deb.nodesource.com/setup_14.x | bash -
# RUN apt-get install -y nodejs

# Expose the ports that the application will run on
EXPOSE 1433 1434

# Set the default command to run when starting the container
CMD ["bash"]
