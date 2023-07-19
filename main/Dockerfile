FROM golang:1.20 AS builder

WORKDIR /usr/src/app

COPY ./fullcycle-rocks.go .

RUN go build -v fullcycle-rocks.go && \
    cp fullcycle-rocks /usr/local/bin/

CMD [ "fullcycle-rocks" ]

FROM scratch

COPY --from=builder /usr/local/bin/fullcycle-rocks /

CMD [ "/fullcycle-rocks" ]