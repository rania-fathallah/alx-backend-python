# 0x02. Python - Async Comprehension

This project explores asynchronous programming in Python, specifically focusing on asynchronous comprehensions and generators. It provides a hands-on approach to understanding how async features can be utilized to handle asynchronous operations efficiently.

## Learning Objectives

- Understand how to write asynchronous functions using `async def`.
- Learn about asynchronous generators and their usage.
- Use `async for` to iterate over asynchronous generators.
- Implement asynchronous comprehensions to gather data from async iterables.

## Project Structure

The project includes the following tasks:

1. **0-async_generator.py**
   - Implements an asynchronous generator function that yields random floating-point numbers after a delay.

2. **1-async_comprehension.py**
   - Uses asynchronous comprehensions to collect the results of the asynchronous generator into a list.

3. **2-measure_runtime.py**
   - Measures the total runtime of running multiple asynchronous comprehensions in parallel using the `asyncio.gather` function.

## Requirements

- Python 3.6 or higher is required to support asynchronous generators and comprehensions.
- Familiarity with Python's `asyncio` library is helpful.

## How to Run

1. Clone the repository or download the project files.
2. Run each script with Python, for example:
   ```bash
   python3 0-async_generator.py
   ```
3. Follow the prompts and outputs to understand the asynchronous behavior.

## Examples

### 0-async_generator.py
This script generates random floating-point numbers asynchronously:
```python
async def async_generator():
    ...
    yield random_value
```

### 1-async_comprehension.py
This script demonstrates how to collect results using async comprehensions:
```python
async def async_comprehension():
    return [value async for value in async_generator()]
```

### 2-measure_runtime.py
Measures the runtime of executing asynchronous comprehensions in parallel:
```python
async def measure_runtime():
    ...
    await asyncio.gather(...)
```

## Learning Resources

- [Python `asyncio` Documentation](https://docs.python.org/3/library/asyncio.html)
- [PEP 525 – Asynchronous Generators](https://peps.python.org/pep-0525/)
- [PEP 530 – Asynchronous Comprehensions](https://peps.python.org/pep-0530/)
