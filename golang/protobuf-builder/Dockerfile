FROM golang:1.24.0

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]