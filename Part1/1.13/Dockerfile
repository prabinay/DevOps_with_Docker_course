FROM golang:1.16

WORKDIR /app

COPY . .

RUN go build -o server

EXPOSE 8080

ENV REQUEST_ORIGIN=http://192.168.150.130:5000

CMD ["./server"]
