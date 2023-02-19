FROM alpine:latest
RUN apk --no-cache add dhcp-helper
EXPOSE 67/tcp 67/udp
ENTRYPOINT ["dhcp-helper", "-n"]