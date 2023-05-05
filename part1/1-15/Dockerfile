FROM alpine:3.17

WORKDIR /usr/src/app

RUN apk update && apk add curl python3
RUN curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl
RUN chmod a+x /usr/local/bin/youtube-dl

ENV LC_ALL=C.UTF-8

ENTRYPOINT ["/usr/local/bin/youtube-dl"]

CMD ["https://imgur.com/gallery/NQWTWXs"]
