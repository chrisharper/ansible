FROM alpine:latest

RUN apk update && apk add hostapd

ADD hostapd.conf /etc/hostapd/hostapd.conf


ENTRYPOINT ["hostapd","/etc/hostapd/hostapd.conf"]
 

