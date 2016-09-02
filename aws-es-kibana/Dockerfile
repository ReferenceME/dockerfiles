FROM alpine:3.3

MAINTAINER Ric Lister <rlister@gmail.com>

RUN apk add --update nodejs && \
    npm install aws-es-kibana@1.0.4 -g

EXPOSE 9200

CMD aws-es-kibana.sh