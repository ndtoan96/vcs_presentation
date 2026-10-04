---
layout: two-cols-header
lineNumbers: true
---

# Extra: Python
## Overview

::left::

- High-level, interpreted programming language
- Dynamic typing
- Simple and readable syntax
- Cross-platform
- Widely used in scripting, data science and machine learning

::right::

```python {all|1-9|11|13,15|all} {lines: true}
def print_str(s):
    if isinstance(s, str):
        print(f"'{s}' is a string with these characters:")
        for c in s:
            print('-', c)
    elif isinstance(s, int):
        print("A wild int appears")
    else:
        print(f"{s} is not a string, it is a {type(s)}")

a = 12345678901234567890123456789123456789123456789
print_str(a)
a = 'Hello world'
print_str(a)
a = [1,2,3]
print_str(a)
```
---

# Extra: Python
## Environment and project management
### Why?

<img class="scale-75 mx-auto" src="/images/python_one_env.png" />

---

# Extra: Python
## Environment and project management
### Why?
<img class="scale-75 mx-auto" src="/images/python_two_envs.png" />

---
layout: two-cols-header
---

# Extra: Python
## Environment and project management
### Why?

::left::
#### Local virtual env
- `uv` <-- Recommended
- `poetry`
- `pdm`
- `pipenv`
- ...

::right::
#### Global virtual env
- Anaconda (commercial license)
- Miniconda (commercial license)
- Miniforge (free)

---
layout: statement
---

# Demo