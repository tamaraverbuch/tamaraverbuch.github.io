# 🚀 Confluent in Python

Using Confluent’s Python client for Kafka.

## Overview
Confluent provides a robust Python client for Kafka that simplifies producing and consuming messages.

## Installation
Install the client with the following command:

pip install confluent-kafka

## Learning Resources

- **[Confluent Python Client Documentation](https://docs.confluent.io/clients-confluent-kafka-python/current/overview.html)**: Official documentation for Confluent’s Python client.
- **[Introduction to Confluent Kafka in Python - YouTube](https://www.youtube.com/playlist?list=PLa7VYi0yPIH1odVnZC430071CVD_4Sx1e)**: Video tutorials on using Confluent Kafka in Python.

[🔙 Back to Kafka Overview](../../README.md#-kafka)

## Example Code
Using Confluent's Python client to produce a message:

```python
from confluent_kafka import Producer

# Set up the producer with Confluent configuration
conf = {'bootstrap.servers': 'localhost:9092'}
producer = Producer(**conf)

# Define a delivery callback function
def delivery_report(err, msg):
    if err is not None:
        print('Message delivery failed: {}'.format(err))
    else:
        print('Message delivered to {} [{}]'.format(msg.topic(), msg.partition()))

# Produce a message
producer.produce('test-topic', key='key', value='Hello, Confluent!', callback=delivery_report)
producer.flush()
