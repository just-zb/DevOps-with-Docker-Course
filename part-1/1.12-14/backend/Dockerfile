FROM golang:latest

EXPOSE 8080

COPY . .


RUN go build

RUN go test ./...

ENV REQUEST_ORIGIN=http://localhost:5001
CMD ./server
