FROM golang:1.16

EXPOSE 5000

WORKDIR /usr/src/app

COPY . .

RUN go build

CMD ["./server"]
