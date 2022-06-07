FROM golang:1.17.11-alpine3.16

MAINTAINER Ayaz Ayupov ayaz@releaseband.com

RUN apk update && apk add --no-cache \
	libc6-compat \
	&& rm -rf /var/cache/apk/*

ENV CGO_ENABLED=1 GOOS=linux
