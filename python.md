# 📘 Complete Python Programming Reference

This repository contains a **complete structured reference of Core Python (Beginner to Advanced)**.  
Useful for learning, revision, interviews, and exams.

---

## 📌 1. Python Overview

- High-level programming language  
- Interpreted language  
- Dynamically typed  
- Object-oriented & multi-paradigm  
- Cross-platform  
- Garbage-collected  
- Large standard library  
- Supports procedural, OOP, and functional programming  

---

## 📌 2. Syntax & Basics

- Indentation defines code blocks  
- Case-sensitive language  
- Comments start with `#`  
- Multi-line strings using triple quotes  
- Statements usually end without semicolon  
- REPL (Interactive Mode)  
- Docstrings using triple quotes  
- Encoding declaration (`# -*- coding: utf-8 -*-`)  

---

## 📌 3. Keywords

`if`, `else`, `elif`, `for`, `while`, `break`, `continue`, `pass`,  
`def`, `return`, `class`, `try`, `except`, `finally`, `raise`,  
`import`, `from`, `as`, `with`, `lambda`, `True`, `False`, `None`,  
`global`, `nonlocal`, `assert`, `del`, `yield`, `async`, `await`,  
`in`, `is`, `not`, `and`, `or`

---

## 📌 4. Variables & Data Types

### Numeric
- `int`
- `float`
- `complex`

### Text
- `str`

### Boolean
- `bool`

### Sequence
- `list`
- `tuple`
- `range`

### Mapping
- `dict`

### Set
- `set`
- `frozenset`

### Binary Types
- `bytes`
- `bytearray`
- `memoryview`

### None Type
- `None`

---

## 📌 5. Type Conversion Functions

`int()`  
`float()`  
`str()`  
`bool()`  
`list()`  
`tuple()`  
`set()`  
`dict()`  
`bytes()`

---

## 📌 6. Operators

### Arithmetic
`+` `-` `*` `/` `//` `%` `**`

### Comparison
`==` `!=` `>` `<` `>=` `<=`

### Logical
`and` `or` `not`

### Assignment
`=` `+=` `-=` `*=` `/=` `//=`

### Identity
`is` `is not`

### Membership
`in` `not in`

### Bitwise
`&` `|` `^` `~` `<<` `>>`

---

## 📌 7. Conditional Statements

- `if`
- `elif`
- `else`
- Nested conditions
- Ternary operator (`x if condition else y`)
- Match-case (Python 3.10+)

---

## 📌 8. Loops

- `for`
- `while`
- `break`
- `continue`
- `pass`
- `else` with loops
- `range()` usage

---

## 📌 9. Data Structures

### List (Ordered, Mutable)
Methods:
`append()` `extend()` `insert()` `remove()` `pop()` `clear()`  
`sort()` `reverse()` `count()` `index()` `copy()`

### Tuple (Ordered, Immutable)

### Dictionary (Key-Value, Mutable)
Methods:
`keys()` `values()` `items()` `get()` `update()`  
`pop()` `popitem()` `setdefault()` `clear()` `copy()`

### Set (Unordered, Unique)
Methods:
`add()` `remove()` `discard()` `union()`  
`intersection()` `difference()` `symmetric_difference()`  
`issubset()` `issuperset()`

### Slicing
`sequence[start:stop:step]`

---

## 📌 10. Strings

Common Methods:
`lower()` `upper()` `strip()` `replace()` `split()`  
`join()` `find()` `count()` `startswith()` `endswith()`  
`isdigit()` `isalpha()` `isalnum()`

### String Formatting
`% formatting`  
`format()`  
`f-strings`

---

## 📌 11. Functions

- `def`
- `return`
- Default parameters
- Keyword arguments
- `*args`
- `**kwargs`
- Lambda functions
- Recursive functions
- Annotations (Type hints)
- Docstrings
- LEGB scope rule
- `global`
- `nonlocal`

---

## 📌 12. Built-in Functions

`print()`  
`input()`  
`len()`  
`type()`  
`range()`  
`sum()`  
`min()`  
`max()`  
`abs()`  
`round()`  
`sorted()`  
`map()`  
`filter()`  
`zip()`  
`enumerate()`  
`all()`  
`any()`  
`dir()`  
`id()`  
`help()`  
`open()`

---

## 📌 13. Modules & Imports

- `import module`
- `from module import name`
- `import module as alias`
- `__name__ == "__main__"`

Standard Modules:
`math` `random` `datetime` `os` `sys` `time`  
`itertools` `collections` `functools` `copy` `enum`

Important Utilities:
- `collections.Counter`
- `collections.defaultdict`
- `collections.deque`
- `functools.reduce`
- `functools.lru_cache`
- `copy.copy()`
- `copy.deepcopy()`

---

## 📌 14. File Handling

Modes:
`r` `w` `a` `rb` `wb`

Methods:
`read()` `write()` `readline()` `readlines()` `close()`

Use `with` statement for safe handling.

---

## 📌 15. Exception Handling

- `try`
- `except`
- `finally`
- `raise`
- `assert`

Common Exceptions:
`ValueError` `TypeError` `ZeroDivisionError`  
`IndexError` `KeyError` `FileNotFoundError`  
`ImportError` `AttributeError`

---

## 📌 16. Object-Oriented Programming

- Class
- Object
- Constructor (`__init__`)
- Instance variables
- Class variables
- Methods
- `@staticmethod`
- `@classmethod`
- `@property`
- Inheritance
- Method overriding
- Polymorphism
- Encapsulation
- Abstraction
- Dunder (Magic) Methods
- Dataclasses

---

## 📌 17. Advanced Python

- List Comprehension
- Dictionary Comprehension
- Set Comprehension
- Generators (`yield`)
- Iterators
- Decorators
- Context Managers
- Magic Methods (`__str__`, `__len__`, etc.)
- Type Hinting (`typing` module)
- Enum
- NamedTuple

---

## 📌 18. Async & Parallelism

- `async`
- `await`
- `asyncio`
- `threading`
- `multiprocessing`
- GIL concept

---

## 📌 19. Memory & Internals

- Mutable vs Immutable
- Shallow Copy
- Deep Copy
- Reference Counting
- Garbage Collection
- Object Identity
- Global Interpreter Lock (GIL)

---

## 📌 20. Virtual Environments

`python -m venv env_name`  
Activate environment  
`pip install package`  
`pip freeze > requirements.txt`

---

## 📌 21. Coding Best Practices

- Follow PEP 8  
- Write clean and modular code  
- Use meaningful names  
- Handle exceptions properly  
- Use virtual environments  
- Write docstrings  
- Use logging instead of print in production  
- Write unit tests  

---

## ✅ Notes

- Covers complete Core Python
- Beginner to Advanced
- No external frameworks included
- Suitable for interviews and deep revision
- Structured for quick reference

---

### ⭐ If this repository helped you, consider starring it  
Happy Coding 🐍
