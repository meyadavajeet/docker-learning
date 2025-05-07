FROM ubuntu:22.04

# set the working directory
WORKDIR /app


# copy the current directory contents into the container at /app
COPY script.sh .

# Make the script executable
RUN chmod +x script.sh

# run the script
CMD ["./script.sh"]