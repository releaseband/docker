FROM golang:1.24rc3

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]