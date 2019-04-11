FROM mariadb

ADD my.cnf /etc/mysql/my.cnf
ADD ${DB_PATH} /var/lib/mysql

EXPOSE 3306

CMD ["mysqld"]
