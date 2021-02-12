FROM redis:6-alpine

ARG REDIS_PASSWORD=secret
ENV REDIS_PASSWORD ${REDIS_PASSWORD}

CMD redis-server --requirepass ${REDIS_PASSWORD}
