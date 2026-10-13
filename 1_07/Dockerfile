# Start from the alpine image
FROM ubuntu:24.04

RUN apt-get update

RUN apt-get install -y curl

WORKDIR /usr/src/app/

# Copy the script.sh file from this location to /usr/src/app/ creating /usr/src/app/script.sh.
COPY script.sh .
RUN chmod +x script.sh

# When running Docker run the command will be ./script.sh
CMD ["./script.sh"]
