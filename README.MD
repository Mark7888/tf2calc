# PricesTF Python API

This modul is a simple python package to calcualte tf2 prices.

### Installation

This module requires [Python](https://www.python.org/) v3+ to run.

For install the module type this to your command line...

```sh
pip install tf2calc
```

### Syntax
```text
calculate(<amount>, <"type">)
- amount (intriger)
- type (string):
  - "scrap"
  - "rec"
  - "ref"
  - "key"
  - "earbuds"
```

### Quick Example
```py
from tf2clac import *

calculation = calculate(1, "ref")
```

It will return a dictionary with the calculated values.
```json
{"scrap": 9, "rec": 3, "ref": 1, "key": 0.02, "earbuds": 0.0}
```
If you write an unknown type, it will return `0`.

License
----

MIT
