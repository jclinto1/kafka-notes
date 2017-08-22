# kafka-notes

## Create Topic

bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 3 --topic some_topic

## Delete Topic

bin/kafka-topics.sh --zookeeper localhost:2181 --delete --topic some_topic

## Describe Topic

bin/kafka-topics.sh --describe --zookeeper localhost:2181 --topic some_topic

## List Topics

bin/kafka-topics.sh --list --zookeeper localhost:2181
