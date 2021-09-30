FROM alpine:3.14.2
RUN apk --update add postgresql-client && rm -rf /var/cache/apk/*
ENTRYPOINT ["psql"]
