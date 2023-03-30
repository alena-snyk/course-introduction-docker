FROM alpine:3.17.3

COPY ./docker-entrypoint.sh /

ENTRYPOINT ["/docker-entrypoint.sh"]

CMD ["ping", "8.8.8.8"]