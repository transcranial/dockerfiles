FROM alpine:3.22

RUN apk --update add postgresql-client && rm -rf /var/cache/apk/*

# Add Amazon RDS root certificates
RUN wget -O /etc/ssl/certs/rds-combined-ca-bundle.pem \
    https://truststore.pki.rds.amazonaws.com/global/global-bundle.pem \
  && chmod 0644 /etc/ssl/certs/rds-combined-ca-bundle.pem

ENTRYPOINT ["psql"]
