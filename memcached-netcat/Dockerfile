FROM memcached:1.5-alpine

USER root

RUN apk add --no-cache netcat-openbsd

USER memcache

HEALTHCHECK --start-period=3s --timeout=2s --interval=10s CMD ["/usr/bin/nc","-zv","127.0.0.1","11211"]
