FROM golang:1.24.2

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]