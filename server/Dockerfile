FROM golang:1.14-alpine

WORKDIR /server

COPY . .

ENV GO111MODULE=on

RUN apk add git

RUN go get github.com/pilu/fresh

CMD ["fresh"]