FROM golang:1.24.1

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]