# Python More Data Structures

In Python, data structures are containers that hold and organize data. They allow you to work with data in various ways. This guide will introduce you to more advanced data structures in Python.

## Lists

A list is a collection of items. You can add, remove, and access items in a list. Lists are defined using square brackets `[ ]`.

Example:
```python
my_list = [1, 2, 3, 4, 5]
```

## Tuples

Tuples are similar to lists but are immutable, meaning you can't change their content after creation. Tuples are defined using parentheses `( )`.

Example:
```python
my_tuple = (1, 2, 3)
```

## Sets

Sets are collections of unique items. They are defined using curly braces `{ }`.

Example:
```python
my_set = {1, 2, 3}
```

## Dictionaries

Dictionaries store data in key-value pairs. You can use a key to look up a corresponding value. Dictionaries are defined using curly braces `{ }` with key-value pairs separated by colons `:`.

Example:
```python
my_dict = {'name': 'John', 'age': 25}
```

## List Comprehensions

List comprehensions are a concise way to create lists based on existing lists or other iterables. They can make your code more readable.

Example:
```python
squared_numbers = [x**2 for x in [1, 2, 3, 4, 5]]
```

## Set Comprehensions

Set comprehensions are similar to list comprehensions but create sets instead of lists. They are useful for creating unique collections.

Example:
```python
unique_numbers = {x % 2 for x in [1, 2, 3, 4, 5]}
```

## Dictionary Comprehensions

Dictionary comprehensions allow you to create dictionaries using a compact syntax.

Example:
```python
squared_dict = {x: x**2 for x in [1, 2, 3, 4, 5]}
```
