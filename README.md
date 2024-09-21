# emqxmqtt
a emqx mqtt broker configuration using docker


#### run
```shell
docker-compose up -d
```

#### check cluster status
```shell
docker exec -it emqx1 sh -c "emqx ctl cluster status"
```
