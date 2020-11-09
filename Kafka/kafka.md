# Kafka

##### 1. connection, unavailable broker

> Connection to node -1 (/127.0.0.1:9092) could not be established. Broker may not be available.

Seems like the server not started


- Go to `/kafka_2.13-2.6.0` path

- run zookeeper  `bin/zookeeper-server-start.sh config/zookeeper.properties`

- Run Kafka  `bin/kafka-server-start.sh config/server.properties`