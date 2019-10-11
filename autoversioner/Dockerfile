FROM debian:stretch

WORKDIR /workspace
ADD gopath/bin /
# added for debugging
COPY Dockerfile Dockerfile
CMD ["ls", "-ltr", "/"]
