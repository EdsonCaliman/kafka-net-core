# Kafka Producer and Consumer #

Command to create a topic, run on cmd:

docker-compose exec broker kafka-topics --create --bootstrap-server \localhost:9092 --replication-factor 1 --partitions 1 --topic test-topic

