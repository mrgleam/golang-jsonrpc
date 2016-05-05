FROM alpine

#RUN apk --update add curl
RUN mkdir /go
RUN export GOPATH=/go
ENV GOPATH /go 
RUN export PATH=$PATH:$GOPATH/bin
ENV PATH $PATH:$GOPATH/bin

WORKDIR /go 

COPY server /go/bin/
CMD /go/bin/server
