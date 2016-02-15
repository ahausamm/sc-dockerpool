FROM golang

MAINTAINER Adrian Hausammann 

RUN go get github.com/ahausamm/staticcms-images/default
RUN go install github.com/ahausamm/staticcms-images/default
ENTRYPOINT /go/bin/staticcms-images/default/main -client=$client