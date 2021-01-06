FROM golang:1.15.6

MAINTAINER Ayaz Ayupov ayaz@releaseband.com

RUN apt-get update && \
	apt-get -y install make g++

COPY Makefile .
RUN make build

RUN rm -rf /var/lib/apt/lists/* && \
	rm -rf Makefile

ENTRYPOINT ["/bin/bash"]