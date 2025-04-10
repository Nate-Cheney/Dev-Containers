FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Update package list and install Python and pip
RUN apt update && \
    apt install -y python3 python3-dev python3-pip

# Install Jupyter and ipykernel system-wide using the system Python
RUN /usr/bin/python3 -m pip install jupyter ipykernel
