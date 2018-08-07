FROM golang:1.10

WORKDIR $GOPATH/src/github.com/
RUN mkdir service1

COPY ./main.go ./service1/

RUN CGO_ENABLED=0 GOOS=linux go build -a -installsuffix nocgo -o service1
