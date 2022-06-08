get-protocol-buffer-dependencies:
	go get github.com/gogo/protobuf/proto
	go get github.com/golang/protobuf/protoc-gen-go
	go get github.com/gogo/protobuf/protoc-gen-gogo
	go get github.com/gogo/protobuf/gogoproto
	go get -u github.com/gogo/protobuf/protoc-gen-gofast
	go get -u github.com/gogo/protobuf/protoc-gen-gogofast
	go get -u github.com/gogo/protobuf/protoc-gen-gogofaster
	go get -u github.com/gogo/protobuf/protoc-gen-gogoslick

install-protocol-buffer:
	apt install -y protobuf-compiler
	protoc --version

use-ssh-for-bitbucket:
	git config \
    --global \
    url."git@bitbucket.org".insteadOf \
    "https://bitbucket.org"


install:
	apt-get update
	apt-get -y install make g++
	apt install -y protobuf-compiler
	protoc --version

build: install
	make install-protocol-buffer
	make get-protocol-buffer-dependencies
	make use-ssh-for-bitbucket