FROM alpine:3.18.2
RUN apk --update add postgresql-client && rm -rf /var/cache/apk/*
ENTRYPOINT ["psql"]
