FROM golang:1.23rc2

RUN adduser --disabled-password --gecos '' api
USER api

WORKDIR /go/src/app
COPY . .

RUN go get github.com/pilu/fresh
RUN go get ./...

CMD [ "fresh" ]
