FROM alpine-nginx-base:1.0.0

LABEL maintainer="proteogenic@localhost"
LABEL version="1.0.0"

# support running as arbitrary user which belogs to the root group
RUN chmod g+rwx /var/cache/nginx /var/run /var/log/nginx

RUN addgroup nginx root
USER nginx