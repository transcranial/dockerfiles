FROM alpine:3.20.2
RUN apk --update add postgresql-client && rm -rf /var/cache/apk/*
ENTRYPOINT ["psql"]
