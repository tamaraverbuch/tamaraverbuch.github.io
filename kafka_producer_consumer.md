# 🚀 Kafka Producer/Consumer

Overview of producing and consuming messages in Kafka.

## Producers
Producers send data to Kafka topics. A producer assigns messages to specific partitions within a topic.

## Consumers
Consumers read data from Kafka topics. Consumers in the same group share the work of consuming messages in a topic.

## Example Code
Here’s an example of a Kafka producer written in Python:

```python
from kafka import KafkaProducer

# Set up the producer
producer = KafkaProducer(bootstrap_servers='localhost:9092')

# Send a message to the topic named 'test-topic'
producer.send('test-topic', b'Hello, Kafka!')
producer.flush()  # Ensure all messages are sent before exiting

## Learning Resources

- **[Kafka Producer and Consumer Documentation](https://kafka.apache.org/documentation/#producerapi)**: Official documentation on using producers and consumers in Kafka.
- **[Getting Started with Kafka Producer/Consumer - YouTube](https://www.youtube.com/watch?v=ChwWu2sNtTo)**: Video tutorial on setting up Kafka producers and consumers.

[Back to Kafka Overview](README.md#kafka)
