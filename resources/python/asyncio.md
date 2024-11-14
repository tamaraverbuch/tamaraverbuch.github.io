# 🐍 Asyncio

Asynchronous programming with asyncio.

## Overview
Asyncio is a Python library used for asynchronous programming. It allows you to write concurrent code using the `async` and `await` keywords, which is highly useful for handling I/O-bound tasks in data engineering.

## Key Concepts
- **Coroutines**: Functions defined with `async def` and run asynchronously.
- **Event Loop**: Orchestrates and runs asynchronous tasks.
- **Tasks and Futures**: Manage asynchronous execution of code.

## Learning Resources

- [Asyncio Documentation](https://docs.python.org/3/library/asyncio.html): Official documentation for Python's asyncio library.
- [Async Programming in Python - YouTube](https://www.youtube.com/watch?v=Qb9s3UiMSTA): Video tutorial on asynchronous programming in Python.

⬅️ [Back to Python Overview](../../README.md#-python-for-data-engineering)


## Example Code
Here's an example of using asyncio to run tasks concurrently:

```python
import asyncio

async def fetch_data():
    print("Fetching data...")
    await asyncio.sleep(2)
    print("Data fetched!")

async def main():
    await asyncio.gather(fetch_data(), fetch_data())

# Run the main function
asyncio.run(main())
