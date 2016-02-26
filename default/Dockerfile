FROM golang

MAINTAINER Adrian Hausammann 

RUN go get github.com/ahausamm/sc-images/default
RUN go install github.com/ahausamm/sc-images/default
ENTRYPOINT /go/bin/default -client=$client
