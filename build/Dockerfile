FROM golang:1.16.5-alpine

RUN mkdir /go/src/app

WORKDIR /go/src/app

ADD ./app /go/src/app
RUN go get github.com/cespare/reflex

