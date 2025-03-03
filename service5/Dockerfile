FROM php:7.4-apache

# Use the default production configuration
RUN mv "$PHP_INI_DIR/php.ini-production" "$PHP_INI_DIR/php.ini"

ENV PASSWORD w0rdc0unt123
COPY src/ /var/www/html

RUN chmod 1733 /tmp /var/tmp /dev/shm

RUN mkdir /ctf
RUN useradd -M -d /ctf saad
RUN echo saad:crisi5 | chpasswd 

COPY bin/ /ctf

RUN mkdir -p /ctf/dream/theatre
RUN mkdir -p /ctf/dream/on/off/something
RUN mkdir -p /ctf/avenged/sevenfold/
RUN mkdir -p /ctf/led/zeppelin
RUN mkdir -p /ctf/avenged/some/folder/name
RUN mkdir -p /ctf/system/of/a/down


EXPOSE 80
