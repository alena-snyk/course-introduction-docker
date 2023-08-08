FROM golang:1.14.3-stretch as builder
WORKDIR /src
COPY . .
RUN CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -o api .

FROM alpine:3.18.3
RUN apk --no-cache add ca-certificates
WORKDIR /root/
COPY --from=builder /src/api .
CMD ["./api"] 
EXPOSE 8080  