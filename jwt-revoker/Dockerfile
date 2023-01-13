FROM golang:1.20rc3

RUN mkdir /app
WORKDIR /app
COPY . .

RUN GOPROXY=https://goproxy.io go get -d -v ./...
RUN go install .

EXPOSE 8080

CMD ["jwt-revoker"]
