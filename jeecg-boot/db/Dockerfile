FROM mysql:5.7.20

MAINTAINER jeecgos@163.com

ENV TZ=Asia/Shanghai

RUN ln -sf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

COPY ./jeecgboot-mysql-5.7.sql /docker-entrypoint-initdb.d