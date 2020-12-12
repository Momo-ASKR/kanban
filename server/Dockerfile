FROM golang:1.14-alpine

WORKDIR /go/src/github.com/Momo-ASKR/kanban/server

COPY . .

ENV GO111MODULE=on

RUN apk add git

RUN go get github.com/pilu/fresh

CMD ["fresh"]