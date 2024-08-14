# Use a base image
FROM mcr.microsoft.com/devcontainers/python:3.10

# Install OS-level packages
RUN apt-get update && apt-get install -y \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*

# Install Python packages
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
