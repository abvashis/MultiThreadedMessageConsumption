https://howtoprogram.xyz/2016/09/25/spring-kafka-multi-threaded-message-consumption/

create kafka topic:

kafka-topics --create --zookeeper localhost:2181  --replication-factor 1 --partitions 3 --topic SpringKafkaTopic