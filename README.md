# wikimedia-docker
deploy wiki/wikimedia using docker and fig.

component including:
- wikimedia
- mysql


## deps
* [docker](https://www.docker.com/)
* [fig](http://www.fig.sh/)

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


