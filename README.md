# task-queue

A bounded worker pool with backpressure, retries and graceful shutdown.

## Why

Mostly written for my own projects, but it may be useful to someone else.

## Install

```bash
pip install task-queue
```

## Usage

```python
from task_queue import taskQueue

result = taskQueue("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
