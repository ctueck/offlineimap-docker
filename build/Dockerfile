FROM alpine:edge

RUN apk add --no-cache offlineimap ca-certificates && rm -rf /var/cache/apk/*

# offlineimap wants all certificates in one file
RUN cd /usr/share/ca-certificates && cat mozilla/*.crt > all.crt

