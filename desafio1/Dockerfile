FROM golang:1.14-buster

COPY app.go /app/app.go

WORKDIR /app

RUN go build app.go

CMD ["./app"]