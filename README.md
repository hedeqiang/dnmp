<h1 align="center"> PHP Docker 开发环境 </h1>

<p align="center">Docker</p>

> 移植 laradock 环境，去掉 workspace ，每次安装贼痛苦，索性去掉。

## 使用
```
git clone https://github.com/hedeqiang/dnmp.git
cd dnmp

# 启动全部
docker-compose up

# 仅启动需要的
docker-compose up -d nginx mariadb redis
```

## 支持软件
- Nginx
- php-fpm
- Mariadb
- Redis
- ElasticSearch
- Kibana
- Logstash


> 如有需要可以再此基础上继续添加其他软件 

## License

MIT
