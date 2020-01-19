# This is terraform with dood(Docker outside of Docker) on Docker

Could you please use this code when you don't want to pollute your local environment.

## How to use

```
$ cp .env.example .env
$ vim .env
$ docker-compose run --build
$ docker exec -it YOUR_IMAGE_NAME
```

## Use Case

 - Pulling terraform source code from github and apply.
 - Building your image using docker.
 - Deploying source code to aws using ecs-cli or aws-cli If you want.


