#mariadb

FROM debian:bullseye

RUN apt-get -y update

RUN apt-get -y install mariadb-server

COPY tools/script.sh /

EXPOSE 3306

RUN chmod +x /script.sh

CMD [ "./script.sh" ]
