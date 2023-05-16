#start imageu 
FROM alpine:latest

WORKDIR /usr/src/app

#copy script
COPY script.sh .

#adding curl
RUN apk add curl

#Giving permission to run the script
RUN chmod +x script.sh

# Set the default command to run when the container starts
CMD ./script.sh
