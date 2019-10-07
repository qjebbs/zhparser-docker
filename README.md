# zhparser-docker

PostgreSQL 10.1 并预装中文分词插件 zhparser 1.2.3

用法：

```sh
docker build -t postgresql-zhparser .
docker run -d --name dbname \
        -p 5432:5432/tcp \
        -e POSTGRES_USER=user \
        -e POSTGRES_PASSWORD=passwd \
        postgresql-zhparser
```
