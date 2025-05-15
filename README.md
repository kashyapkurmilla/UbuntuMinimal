# Minimal Ubuntu Terminal Container

This Docker image provides a minimal Ubuntu 22.04 environment with essential terminal tools like `vim`, `nano`, `curl`, and `sudo`. Perfect for quick shell-based tasks, scripting, or as a base image for lightweight development.

## Features

- Based on `ubuntu:22.04`
- Pre-installed: `bash`, `vim`, `nano`, `curl`, `wget`, `less`, `sudo`, `net-tools`, `ping`
- Non-root user for safer usage
- Clean and small footprint (~120 MB)

## Usage

### Build the Image

```bash
docker build -t mini-ubuntu-os .
