# ruby
#
# VERSION               0.0.1

FROM      php:alpine

MAINTAINER Gen Takahashi "gendosu@gmail.com"

ENV LANG=ja_JP.UTF-8

# Timezone変更
RUN apk add --update \
    bash \
    tzdata \
    git \
&&  cp /usr/share/zoneinfo/Japan /etc/localtime \
&&  apk del tzdata \
&&  rm -rf /var/cache/apk/*

