FROM golang:1.23.3

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]