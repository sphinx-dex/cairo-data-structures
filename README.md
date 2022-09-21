# cairo-ds

`cairo-ds` is a Cairo library of common data structures (e.g. binary trees, heaps and linked lists), optimised for fast execution, read / write capability and on-chain storage.

Below is a list of implemented and planned data structures. We also indicate their execution efficiency in terms of memory usage and resource requirements.

| Data structure     | Gas cost | Memory holes | No of steps | Status         |
| ------------------ | -------- | ------------ | ----------- | -------------- |
| Singly linked list | - | - | - | In development |
| Doubly linked list | - | - | - | In development |
| Stack | - | - | - | In development |
| Queue | - | - | - | In development |
| Binary search tree | - | - | - | In development |
| Max binary heap | - | - | - | In development |
| Min binary heap | - | - | - | In development |
| Hash table | - | - | - | ✅ |
| Graph | - | - | - | In development |

## Usage

#### Setup a local virtual env

```
python -m venv cairo_venv
source cairo_venv/bin/activate
```

#### Install dependencies
```
pip install -r requirements.txt
```

## Testing

We run unit tests using the `pytest-asyncio` package 