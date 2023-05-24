FROM ubi8/go-toolset:latest

WORKDIR /go/src/app

COPY *.go .

RUN go mod init dispatch && go get
RUN go install

CMD dispatch
