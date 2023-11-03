# Python Import Modules (0x02)

This project is a beginner's guide to understanding how to import modules in Python. Modules are Python files that contain functions, classes, and variables, allowing you to organize your code and reuse it in different programs.

## Table of Contents

- [Getting Started](#getting-started)
- [Importing Built-in Modules](#importing-built-in-modules)
- [Creating Your Own Modules](#creating-your-own-modules)
- [Importing Your Own Modules](#importing-your-own-modules)
- [Importing Third-Party Modules](#importing-third-party-modules)

## Getting Started

To get started, make sure you have Python installed on your computer. You can download Python from the official website: [Python Downloads](https://www.python.org/downloads/).

## Importing Built-in Modules

Python comes with many built-in modules that you can use to perform various tasks. To import a built-in module, use the `import` statement:

```python
import math
```

Now you can use functions and constants from the `math` module:

```python
print(math.sqrt(16))  # Outputs: 4.0
```

## Creating Your Own Modules

You can create your own modules by creating a Python file with your functions and variables. For example, create a file named `my_module.py`:

```python
# my_module.py
def greet(name):
    return f"Hello, {name}!"
```

## Importing Your Own Modules

To use the module you've created, you can import it into your Python script:

```python
import my_module

message = my_module.greet("Alice")
print(message)  # Outputs: Hello, Alice!
```

## Importing Third-Party Modules

Python's strength lies in its rich ecosystem of third-party modules. You can use external modules by installing them using tools like `pip`:

```bash
pip install requests
```

Then, import and use the module in your code:

```python
import requests

response = requests.get("https://www.example.com")
print(response.status_code)  # Outputs the HTTP status code
```

