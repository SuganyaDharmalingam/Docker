#base image for docker container from dockerhub
FROM ubuntu:latest

# Set the working directory in the image
WORKDIR /app

#copy the files from the host file system to the image file system
COPY . /app

#Install the necessary packages
RUN apt-get update && apt-get install -y python3 python3-pip

# Set environment variables
ENV NAME World

# Run a command to start the applciation
CMD ["python3", "app.py"]
