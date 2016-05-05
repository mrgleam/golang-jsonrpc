FROM frolvlad/alpine-go
RUN apk --update add curl-dev gcc g++
RUN mkdir /go
RUN mkdir /go/src
RUN mkdir /go/bin
RUN export GOPATH=/go
ENV GOPATH /go
ENV GOBIN /go/bin
RUN export PATH=$PATH:$GOPATH/bin
ENV PATH $PATH:$GOPATH/bin

WORKDIR /go
