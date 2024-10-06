# Docker "Hello, Captain!" Project

This project demonstrates how to create a basic Dockerfile that prints "Hello, Captain!" to the console when executed.

## Project Overview

The Dockerfile provided in this repository builds a Docker image based on the `alpine:latest` base image. When the container created from this image is run, it will print "Hello, Captain!" to the console and then exit.

## Requirements

To complete this project, you need to meet the following requirements:

- The Dockerfile should be named **Dockerfile**.

- The Dockerfile should reside in the **root directory** of the project.
- The Docker image should use **`alpine:latest`** as the base image.
- The Dockerfile should include a single command to print **"Hello, Captain!"** to the console before exiting.

## Dockerfile Instructions

This is a simple Dockerfile with minimal configuration. Below is an example of what your `Dockerfile` should look like:

```Dockerfile
# Use the alpine base image
FROM alpine:latest

# Print "Hello, Captain!" and exit
CMD echo "Hello, Captain!"
```

## Project Link

[Project link](https://roadmap.sh/projects/basic-dockerfile)
