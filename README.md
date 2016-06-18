# bind-docker

https://github.com/sameersbn/docker-bind/blob/master/README.md


## Get it, run it
```
$ git clone  git@github.com:carlosguillen/bind-docker.git
$ cd bind-docker 
$ mkdir -p /srv/docker/bind
$ sudo docker-compose up
```

https://github.com/sameersbn/docker-bind/blob/master/README.md

This is basically sameershbn's image. 
I just added some fake zone data for noobs like mua :stuck_out_tongue:

Edit, replace or remove zone files from the shared volume located here:
```
/srv/docker/bind/bind/etc/
```

You can also manage the zones via the web portal at https://server-address:10000
Default credentials root/password. Read sameersbn's README for more settings etc.
