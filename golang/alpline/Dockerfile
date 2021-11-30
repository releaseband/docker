FROM golang:1.17.3-alpine3.15

MAINTAINER Ayaz Ayupov ayaz@releaseband.com

RUN apk update && apk add --no-cache \
	libc6-compat \
	&& rm -rf /var/cache/apk/*

ENV CGO_ENABLED=1 GOOS=linux
