FROM alpine:latest

RUN apk update --update && \
    apk add --no-cache aria2 && \
    rm -rf /var/cache/apk/* && \
    mkdir /data && \
    chmod 777 /data


WORKDIR /data
EXPOSE 6800
VOLUME /data
ENTRYPOINT ["aria2c","--enable-rpc","--rpc-listen-all"]