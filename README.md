# tokuo-sand-docker-compose

# command
## start, stop, remove
If you want to run your services in the background, you can pass the -d flag 
```
docker-compose up -d
docker-compose ps
docker-compose stop
docker-compose down
```

## action
コンテナが動いていないときにコンテナを起動
```
docker-compose run web env
```

起動しているコンテナを操作
```
# docker-compose exec <service> <command>
docker-compose exec web /bin/bash
```