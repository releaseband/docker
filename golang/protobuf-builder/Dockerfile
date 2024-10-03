FROM golang:1.23.1

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]