## Docker Load Balancer Application

Load Balancing Node.js Application with Docker and HAProxy

--------
```
$ git clone https://github.com/emrahyumuk/docker-load-balancer-app.git
```

```
$ cd docker-load-balancer-app
```

```
$ docker-compose build
```

```
$ docker-compose up -d 
```

```
$ docker-compose scale web=5
```
--------

You can test http://localhost:7000 on browser. 