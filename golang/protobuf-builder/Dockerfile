FROM golang:1.17.11

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]