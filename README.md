# Five Python Parallelization Methods

This repository demonstrates five different methods to perform parallelization in Python. Each method is implemented to fetch and save the top 250 movies from a website.

## Methods

1. **Threading** (`use_threading.py`): Uses `ThreadPool` from the `multiprocessing.pool` module.
2. **Multiprocessing** (`use_multiprocessing.py`): Uses `Pool` from the `multiprocessing` module.
3. **ThreadPoolExecutor** (`use_executor.py`): Uses `ThreadPoolExecutor` from the `concurrent.futures` module.
4. **Asyncio** (`use_asyncio.py`): Uses `asyncio` and `aiohttp` for asynchronous I/O operations.
5. **Non-concurrent** (`io_non_concurrent.py`): A baseline implementation without any parallelization.

## Requirements

Install the required packages using:
```sh
pip install -r requirements.txt
```

## Usage

Run any of the scripts to see the respective parallelization method in action. For example:
```sh
python use_threading.py
```

## License

This project is licensed under the Apache License Version 2.0.

NOTE: The sources have been taken from the [repo](https://github.dev/dongweiming/mp/)