# We will download the latest alpine image
FROM alpine:latest 

# Install packages bind (dhcp server) openrc (the tool that will allows us to run the server)
RUN apk add bind openrc

# This will run our dns server
RUN rc-update -u named


