[Upgrade Docker on CentOS 7](http://stackoverflow.com/questions/26472586/upgrade-docker-on-centos-7)

```shell
# stop the docker service
$ sudo service docker stop

# download the latest docker binary and replace the current outdated docker
$ sudo wget https://get.docker.com/builds/Linux/x86_64/docker-latest -O /usr/bin/docker

# start the docker service
$ sudo service docker start

# check the version
$ sudo docker version

# check the images and containers
$ sudo docker images
$ sudo docker ps
$ sudo docker ps -a
```
