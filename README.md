# docker-laravel

### 配置
复制 env-example 到 .env文件

cd /your/docker/path
cp env-example .env

### 运行
docker-compose up -d nginx mysql redis php-fpm php-worker

具体的细节可以看 laradock

一些env文件主要的配置 
例子：

```
// 项目的路径
APPLICATION=../www/lara-project

// 数据文件存放的文件
DATA_SAVE_PATH=../www/mysql-data

```

over。

