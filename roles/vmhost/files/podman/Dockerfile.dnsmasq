FROM alpine:latest

RUN apk update && apk add dnsmasq

ADD dnsmasq.conf /etc/dnsmasq.conf

ENTRYPOINT ["dnsmasq" ,"-d"]
 

