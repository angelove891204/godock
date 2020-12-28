FROM golang:latest

LABEL maintainer="Jians <294041820@qq.com>"

RUN go env -w GO111MODULE=off

#RUN go get -u github.com/cosmtrek/air

#CMD [ "air" ]

RUN go get -d -v ./...

RUN go get github.com/oxequa/realize
