FROM golang:1.20

WORKDIR /app

COPY . .

RUN go mod init bai5-go

RUN go build -o main .

EXPOSE 8080

CMD ["./main"]