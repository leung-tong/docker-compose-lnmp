# docker-compose-lnmp
lnmp环境搭建

## 目录结构
```
├── README.md
├── docker-compose.yml
├── dockerfile-mysql
├── dockerfile-nginx
├── dockerfile-php-fpm
├── dockerfile-redis
├── mysql
│   └── data
├── nginx
│   ├── log
│   ├── nginx.conf
│   ├── sites
│   │   └── home.conf
│   └── ssl
├── php-fpm
│   └── php.ini
├── redis
│   ├── conf
│   │   └── redis.conf
│   ├── data
│   └── logs
└── www
    └── index.php
```

## 版本
nginx:1.19.10
php:7.2
mysql:5.7
redis:6.0.12
