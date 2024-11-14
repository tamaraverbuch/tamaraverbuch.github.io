# 🐍 FastAPI (REST API)

Building fast REST APIs with FastAPI.

## Overview
FastAPI is a modern, fast (high-performance) web framework for building APIs with Python 3.7+ based on standard Python type hints. It’s particularly useful for building REST APIs for data engineering projects.

## Key Features
- **Fast Development**: Automatic interactive documentation (Swagger UI).
- **High Performance**: Based on Starlette and Pydantic.
- **Dependency Injection**: Simplifies handling dependencies.

## Learning Resources

- [FastAPI Documentation](https://fastapi.tiangolo.com/tutorial/): Official tutorial and documentation for FastAPI.
- [Building APIs with FastAPI - YouTube](https://www.youtube.com/watch?v=iWS9ogMPOI0&t=744s): Video guide on building APIs with FastAPI.

⬅️ [Back to Python Overview](../../README.md#-python-for-data-engineering)


## Example Code
Here's a basic example of creating a FastAPI app:

```python
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
async def read_root():
    return {"message": "Hello, FastAPI!"}

@app.post("/items/")
async def create_item(item: dict):
    return {"item": item}
