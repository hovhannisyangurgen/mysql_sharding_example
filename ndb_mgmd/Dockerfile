FROM mysql/mysql-cluster:7.6.9-1.1.9-cluster

COPY ./my.cnf /etc/my.cnf
COPY ./mysql-cluster.cnf /etc/mysql-cluster.cnf

CMD [ "ndb_mgm" ]