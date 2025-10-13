FROM golang:1.25.2

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]