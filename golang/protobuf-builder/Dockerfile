FROM golang:1.25rc2

COPY Makefile .
RUN make build

ENTRYPOINT ["/bin/bash"]