# kafka 客户端使用


```
# zk 注册中心启动
bin/zookeeper-server-start.sh config/zookeeper.properties


# Kafka 服务启动
bin/kafka-server-start.sh config/server.properties


# 查找 Kafka版本
find ./libs/ -name \*kafka_\* | head -1 | grep -o '\kafka[^\n]*'

```