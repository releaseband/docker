FROM golang:1.25.1

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]