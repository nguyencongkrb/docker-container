
FROM arm64v8/mongo:3.6.22

LABEL maintainer="Cong Nguyen <nguyencongkrb@gmail.com>"

#COPY mongo.conf /usr/local/etc/mongo/mongo.conf

VOLUME /data/mongo /data/configdb

CMD ["mongod"]

EXPOSE 27017