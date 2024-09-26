FROM ubuntu:22.04

# Set the directory in the image
WORKDIR /app

# Copy the files from the host file system to the image file system
COPY . /app

# Update package list, install necessary repositories, and install Python
RUN apt-get update && apt-get install -y python3 python3-pip
# Set environment variables
ENV NAME world

# Run a command to start the application
CMD ["python3", "app.py"]
