## ES分词器安装
```shell
./bin/elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.17.7/elasticsearch-analysis-ik-7.17.7.zip
```

## 启动命令
docker compose up -d [services]

docker compose up -d --force-recreate [services]

docker compose up -d --force-recreate iam auth gateway rocketmq