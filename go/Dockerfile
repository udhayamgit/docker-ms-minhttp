FROM golang:alpine

LABEL maintainer="kiran01bm"

# Install git
RUN apk add --no-cache git

# App workdir
WORKDIR /usr/apps/helloworld

# Copy application source
COPY . .

# Boot up the App
CMD bin/run.sh
