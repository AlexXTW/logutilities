# logutilities

logutilities is a python library for quick logging of functions

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install logutilities.

```bash
pip install logutilities
```

## Usage

```python
from logutilities import log_function

@log_function
def my_function_name():
    print("Hello world!")

```

### In terminal
```
>>> my_function_name()
07/11/2020 11:29:14 PM [my_function_name]
Hello world!
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)