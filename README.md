# python-methods-cheatsheet
# Python Built-in Methods and Functions
This repository serves as a comprehensive reference guide for built-in methods and functions in Python. It provides an organized collection of commonly used methods and functions available in the Python Standard Library, covering various data types and functionalities.

## Content Index

1. [String Methods]( ## String Methods)
2. [List Methods](## List Methods)
3. [Dictionary Methods](#dictionary-methods)
4. [Tuple Methods](#tuple-methods)
5. [Set Methods](#set-methods)
6. [File Object Methods](#file-object-methods)
7. [Boolean Methods](#boolean-methods)
8. [Range Function](#range-function)
9. [Itertools Functions](#itertools-functions)
10. [Math Functions](#math-functions)
11. [Datetime Functions](#datetime-functions)
12. [List Comprehension](#list-comprehension)
13. [Lambda Functions](#lambda-functions)
14. [Built-in Functions](#built-in-functions)
Below is a comprehensive list of commonly used built-in methods and functions in Python, presented in alphabetical order:

## String Methods

```python
str.capitalize()
str.casefold()
str.center(width[, fillchar])
str.count(sub[, start[, end]])
str.encode([encoding[, errors]])
str.endswith(suffix[, start[, end]])
str.expandtabs(tabsize=8)
str.find(sub[, start[, end]])
str.format(*args, **kwargs)
str.format_map(mapping)
str.index(sub[, start[, end]])
str.isalnum()
str.isalpha()
str.isascii()
str.isdecimal()
str.isdigit()
str.isidentifier()
str.islower()
str.isnumeric()
str.isprintable()
str.isspace()
str.istitle()
str.isupper()
str.join(iterable)
str.ljust(width[, fillchar])
str.lower()
str.lstrip([chars])
str.maketrans(x[, y[, z]])
str.partition(sep)
str.replace(old, new[, count])
str.rfind(sub[, start[, end]])
str.rindex(sub[, start[, end]])
str.rjust(width[, fillchar])
str.rpartition(sep)
str.rsplit([sep[, maxsplit]])
str.rstrip([chars])
str.split([sep[, maxsplit]])
str.splitlines([keepends])
str.startswith(prefix[, start[, end]])
str.strip([chars])
str.swapcase()
str.title()
str.translate(table)
str.upper()
str.zfill(width)
```
## List Methods
```python
list.append(item)
list.clear()
list.copy()
list.count(item)
list.extend(iterable)
list.index(item[, start[, end]])
list.insert(index, item)
list.pop([index])
list.remove(item)
list.reverse()
list.sort(*, key=None, reverse=False)
```
## Dictionary Methods
```python
dict.clear()
dict.copy()
dict.fromkeys(iterable[, value])
dict.get(key[, default])
dict.items()
dict.keys()
dict.pop(key[, default])
dict.popitem()
dict.setdefault(key[, default])
dict.update([other])
dict.values()
```
## Tuple Methods
```python
tuple.count(value)
tuple.index(value[, start[, end]])
## Set Methods
set.add(elem)
set.clear()
set.copy()
set.difference(*others)
set.difference_update(*others)
set.discard(elem)
set.intersection(*others)
set.intersection_update(*others)
set.isdisjoint(other)
set.issubset(other)
set.issuperset(other)
set.pop()
set.remove(elem)
set.symmetric_difference(other)
set.symmetric_difference_update(other)
set.union(*others)
set.update(*others)
```
## File Object Methods
```python
file.close()
file.flush()
file.fileno()
file.isatty()
file.read([size])
file.readline([size])
file.readlines([sizehint])
file.seek(offset[, whence])
file.tell()
file.truncate([size])
file.write(str)
file.writelines(lines)
```
## Boolean Methods
```python
bool(x)
```
## Range Function
```python
range(stop)
range(start, stop[, step])
```
## Itertools Functions
```python
itertools.product(*iterables[, repeat])
itertools.combinations(iterable, r)
itertools.permutations(iterable, r=None)
itertools.chain(*iterables)
itertools.islice(iterable, stop)
itertools.count(start=0, step=1)
```
## Math Functions
```python
math.ceil(x)
math.floor(x)
math.trunc(x)
math.pow(x, y)
math.log10(x)
math.log2(x)
math.log1p(x)
math.exp(x)
math.sin(x)
math.cos(x)
math.tan(x)
math.asin(x)
math.acos(x)
math.atan(x)
math.radians(x)
math.degrees(x)
math.sqrt(x)
math.isfinite(x)
math.isinf(x)
math.isnan(x)
math.factorial(x)
math.gcd(a, b)
math.modf(x)
math.copysign(x, y)
math.fabs(x)
math.fmod(x, y)
math.frexp(x)
math.hypot(*args)
```
## File Input/Output Functions
```python
open(file, mode='r', buffering=-1, encoding=None, errors=None, newline=None, closefd=True, opener=None)
file.write(str)
file.writelines(lines)
file.read([size])
file.readline([size])
file.readlines([sizehint])
file.seek(offset[, whence])
file.tell()
file.truncate([size])
file.flush()
file.close()
```
## Datetime Functions
```python
datetime.datetime.now()
datetime.datetime.combine(date, time)
datetime.datetime.strptime(date_string, format)
datetime.datetime.strftime(format)
datetime.datetime.timedelta(days, seconds, microseconds, milliseconds, minutes, hours, weeks)
datetime.datetime.replace(year, month, day, hour, minute, second, microsecond)
```
## List Comprehension
```python
[expression for item in iterable]
[expression for item in iterable if condition]
```
## Lambda Functions
```python
lambda arguments: expression
```
## Built-in Functions
```python
abs(x)
len(s)
type(obj)
id(obj)
callable(obj)
isinstance(obj, classinfo)
issubclass(class, classinfo)
input([prompt])
range(stop)
range(start, stop[, step])
sum(iterable[, start])
sorted(iterable[, key][, reverse])
reversed(sequence)
enumerate(iterable[, start])
zip(*iterables)
map(function, iterable)
filter(function, iterable)
any(iterable)
all(iterable)
```

