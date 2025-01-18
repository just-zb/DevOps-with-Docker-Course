FROM golang:latest

EXPOSE 8080

COPY ./example-backend/. .


RUN go build

RUN go test ./...

ENV REQUEST_ORIGIN=http://localhost:5000
CMD ./server
