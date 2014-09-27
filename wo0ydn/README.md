# Dreams

## Unicode operators

| Old python operator | New awesome one |
|:-------------------:|:---------------:|
| >=                  | ≥               |
| <=                  | ≤               |
| !=                  | ≠               |
| not                 | ¬               |
| x ** 1/2            | √x              |
| x ** 2              | x²              |
| x ** 3              | x³              |

```python
if x ≥ 10 and ¬found:
    # code

if x² ≠ 10:
    # code
```

## More greek letters

Because, it would be awesome to write:

```python
from datetime import datetime

start = datetime.now()
# code
∆t = datetime.now() - start
print("Time: {}ms".format(∆t))
```

## Redefine assignment/equality

| Operation  | Old python | New awesome one |
|:----------:|:----------:|:---------------:|
| Assignment | =          | :               |
| Equality   | ==         | =               |

```python
start: datetime.now()
# code
∆t: datetime.now() - start

if ∆t = 0:
    print("WOW, that was fast!")
```

## Others

* Easy packaging
* All libraries available in Python3
* More cleaner API on some stdlib (like logging.getLogger → logging.get_logger)