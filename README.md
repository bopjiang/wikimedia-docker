# wikimedia-docker
deploy wikimedia using docker.
component including:
- wikimedia
- mysql

## deploy

~~~bash
$ git clone https://github.com/bopjiang/wikimedia-docker.git
$ cd wikimedia-docker
$ fig up -d
~~~

## note
- Mysql password is set in fig.yaml, through MYSQL_ROOT_PASSWORD environment variable
- when setup wikimedia, mysql host should be set as "database"

## TODO
- add memcached


