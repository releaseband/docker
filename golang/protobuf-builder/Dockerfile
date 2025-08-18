FROM golang:1.25.0

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]