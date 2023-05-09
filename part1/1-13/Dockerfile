FROM golang:1.16

WORKDIR /usr/src/app

EXPOSE 8080

COPY . .

ENV PORT=8080

ENV REQUEST_ORIGIN=https://example.com

RUN go build

CMD ["./server"]
