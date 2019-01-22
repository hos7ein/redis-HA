FROM redis
MAINTAINER hos7ein <hossein.a97@gmail.com>

EXPOSE  26379/tcp
RUN     mkdir   -p     /data/log


CMD [ "redis-server", "/data/sentinel.conf", "--sentinel" ]
