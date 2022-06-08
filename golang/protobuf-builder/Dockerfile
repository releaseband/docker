FROM golang:1.17.11

MAINTAINER Ayaz Ayupov ayaz@releaseband.com

ENV version=v1.3.2

RUN apt-get update && \
	apt-get -y install make g++ \
    # install protocol buffer
    apt install -y protobuf-compiler \
    protoc --version \
    # install protocol buffer dependencies
	go get -d github.com/golang/protobuf/protoc-gen-go@v1.4.3 \
	go get -d github.com/gogo/protobuf/proto@$version \
	go get -d github.com/gogo/protobuf/protoc-gen-gogo@$version \
	go get -d github.com/gogo/protobuf/gogoproto@$version \
	go get -d github.com/gogo/protobuf/protoc-gen-gofast@$version \
	go get -d github.com/gogo/protobuf/protoc-gen-gogofast@$version \
	go get -d github.com/gogo/protobuf/protoc-gen-gogofaster@$version \
	# set ssh configs
    &&  git config --global url."git@bitbucket.org".insteadOf "https://bitbucket.org"



ENTRYPOINT ["/bin/bash"]