FROM golang:1.25.3

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]