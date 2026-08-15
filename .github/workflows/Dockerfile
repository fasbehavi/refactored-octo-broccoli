# Use a standard Linux base image
FROM ubuntu:latest

# OPTION 1: Run lscpu during the build process
# The output will show up in your docker build logs
RUN lscpu

# OPTION 2: Run lscpu when the container starts
# The output will show up when you use 'docker run'
CMD ["lscpu"]
