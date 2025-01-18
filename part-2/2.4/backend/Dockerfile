FROM golang:latest


ENV REQUEST_ORIGIN=http://localhost:5000 
ENV REDIS_HOST=redis

EXPOSE 8080

COPY ./example-backend/. .


RUN go build

RUN go test ./...

CMD ./server
