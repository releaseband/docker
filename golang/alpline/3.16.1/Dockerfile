FROM releaseband/alpine:3.16.1

MAINTAINER Ayaz Ayupov ayaz@releaseband.com

RUN apk update && apk add --update-cache \
	libc6-compat \
    libcrypto1.1=1.1.1q-r0 \
    libssl1.1=1.1.1q-r0  \
    && rm -rf /var/cache/apk/*

ENV CGO_ENABLED=1 GOOS=linux
