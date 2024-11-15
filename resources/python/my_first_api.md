# 🐍 My First API

Setting up a basic API that accepts POST requests and sends data to Kafka topics.

## Overview
This example demonstrates how to set up a simple API using FastAPI that accepts POST requests and publishes the data to Kafka topics.

## Learning Resources

- [Simple Kafka Consumer and Producer Using FastAPI - Medium Article](https://lemoncode21.medium.com/simple-kafka-consumer-and-producer-using-fastapi-be1b55deea2): Guide on integrating Kafka with FastAPI.
- [Kafka with FastAPI Tutorial - YouTube](https://www.youtube.com/watch?v=l5NOe3jTEso): Video tutorial on using Kafka with FastAPI.

⬅️ [Back to Python Overview](../../README.md#-python-for-data-engineering)


## Example Code
Creating an API endpoint that processes POST requests:

```python
from fastapi import FastAPI
from kafka import KafkaProducer
import json

app = FastAPI()
producer = KafkaProducer(bootstrap_servers='localhost:9092')

@app.post("/publish/")
async def publish_message(data: dict):
    producer.send('my-topic', json.dumps(data).encode('utf-8'))
    return {"status": "Message sent to Kafka"}
