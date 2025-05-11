FROM golang:1.24.3

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]