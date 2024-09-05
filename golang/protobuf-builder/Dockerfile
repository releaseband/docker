FROM golang:1.22.6

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]