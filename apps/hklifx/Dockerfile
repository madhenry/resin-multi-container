FROM golang:1.8

RUN apk add --update git

CMD git clone --depth=1 https://github.com/brutella/hklifx.git .

CMD go get

CMD go run hklifxd.go -pin 12341234 -v
