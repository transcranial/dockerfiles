FROM alpine:3.15.0
RUN apk --update add postgresql-client && rm -rf /var/cache/apk/*
ENTRYPOINT ["psql"]
