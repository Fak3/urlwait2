This command-line tool tries to connect to specified url until it
receives successful http status code.

## Installation

```
pip install urlwait
```

## Usage
To wait before starting celery worker:

```bash
urlwait myhost/admin && celery -A myapp.app worker
```
