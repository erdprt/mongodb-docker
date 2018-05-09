Samples for using mongodb in docker.
Is supposed to be reused in case applicative stack: add new service in docker-compose

Default config
mongod.conf     :   /etc/mongod.conf (custom configuration in Dockerfile)
data            :   /data/db/ (& /data/configdb?)
log             :   /var/log/mongodb/

Entering the stack: docker exec -it mongodb bash