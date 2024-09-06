FROM golang:1.22.7

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]