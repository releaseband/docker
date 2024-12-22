FROM golang:1.24rc1

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]