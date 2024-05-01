FROM --platform=linux/arm64 golang:1.21-alpine

RUN apk add --no-cache git gcc musl-dev

COPY builder.sh /usr/bin/builder.sh

CMD ["/bin/sh", "/usr/bin/builder.sh"]
