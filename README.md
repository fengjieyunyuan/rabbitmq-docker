
1. 在rabbitmq原有镜像的基础上，制作新镜像（构建延迟队列），在容器启动之后自行启用插件


### 一.制作景象
```
$ cd image   

$ docker build -t myrabbitmq:3.8-management .    


```

### 二. 启动/停止
```
docker-compose up -d （第一次运行）
    docker-compose start （启动服务）
docker-compose stop （停止服务）

