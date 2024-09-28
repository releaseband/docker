FROM golang:latest

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]