# Django + SAAS + Microservices.


### Run The Web Application:
```
sudo docker-compose -f dev.yml up
```

### Stop All Containers:
```
sudo docker stop $(sudo docker ps -a -q)
```

### Remove All Containers:
```
sudo docker rm $(sudo docker ps -a -q)
```