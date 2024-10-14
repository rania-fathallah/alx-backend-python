# 0x01. Python - Async Function

This project focuses on learning asynchronous programming in Python using the `asyncio` module. Asynchronous programming allows for concurrent execution of tasks, improving performance and efficiency, especially in I/O-bound operations.

## Learning Objectives

By the end of this project, you should be able to:

- Understand the basics of asynchronous programming and the `asyncio` module
- Use `async` and `await` keywords to create asynchronous functions
- Manage asynchronous tasks using `asyncio.gather()`, `asyncio.sleep()`, and other utilities
- Write concurrent code that executes multiple tasks simultaneously

## Project Structure

The project consists of Python scripts that demonstrate the use of asynchronous programming with the `asyncio` module:

- `0-basic_async_syntax.py`: Introduction to asynchronous programming with a basic function that uses `asyncio.sleep()`.
- `1-concurrent_coroutines.py`: Demonstrates the concurrent execution of coroutines using `asyncio.gather()`.
- `2-measure_runtime.py`: Measures the runtime of executing multiple coroutines concurrently.
- `3-tasks.py`: Shows how to create and manage tasks using `asyncio.create_task()`.
- `4-task_wait_random.py`: Implements a function that returns a task and uses `asyncio` for delayed execution.
- `5-task_wait_n.py`: Uses the task returned by the previous function to execute multiple tasks concurrently and return their results.
- `6-tasks.py`: Demonstrates advanced use of `asyncio` to manage multiple tasks with various execution times.
