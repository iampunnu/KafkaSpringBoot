# KafkaSpringBoot
Start Zookeper -> bin/zookeeper-server-start.sh config/zookeeper.properties
Start Kafka -> bin/kafka-server-start.sh config/server.properties
Create Topic -> bin/kafka-topics.sh --create --topic katopic --bootstrap-server localhost:9092
Describe Topic -> bin/kafka-topics.sh --describe --topic katopic --bootstrap-server localhost:9092
