FROM ubuntu:22.04

ENV TZ=Asia/Seoul

ARG DEBIAN_FRONTEND=noninteractive

RUN apt update -y && apt install -y git apache2 php php-mysql

RUN a2enmod rewrite
RUN a2enmod headers
