FROM golang:1.25rc1

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]