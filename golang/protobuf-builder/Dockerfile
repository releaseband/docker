FROM golang:1.23.0

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]