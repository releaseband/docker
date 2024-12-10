FROM golang:1.23.4

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]