FROM golang:1.22.7

WORKDIR /go/src/app

COPY *.go .

RUN go mod init dispatch && go get
RUN go install

CMD dispatch
