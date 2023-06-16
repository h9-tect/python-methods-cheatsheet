# python-methods-cheatsheet
# Python Built-in Methods and Functions
This repository serves as a comprehensive reference guide for built-in methods and functions in Python. It provides an organized collection of commonly used methods and functions available in the Python Standard Library, covering various data types and functionalities.

## Content Index
1. [String Methods](#string-methods)
2. [List Methods](#list-methods)
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

Data Structure Comparison in Python

| Data Structure | Name/Identifier | Description                            | Implementation                     | Operations                                                      | Time Complexity                                                | Space Complexity                  | Advantages                                                                                                                                                                       | Disadvantages                                                                                                                                                                                                                                                                                                           | Use Cases                                                                                            | Code Examples                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Mutable/Immutable | Ordering     | Duplicate Elements | Memory Overhead              | Iteration                                                      | Sorting                                                        | Lookup Efficiency                                  | Memory Efficiency                                 | Modifiability              |
|----------------|-----------------|----------------------------------------|-----------------------------------|-----------------------------------------------------------------|----------------------------------------------------------------|-----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|--------------|-------------------|------------------------------|----------------------------------------------------------------|----------------------------------------------------------------|----------------------------------------------------|---------------------------------------------------|----------------------------|
| List           | list            | Mutable sequence of elements            | Dynamic array                      | Access, Insertion, Deletion, Slicing, Concatenation              | Access: O(1)<br>Search: O(n)<br>Insertion: O(n)<br>Deletion: O(n) | O(n)                              | Versatile, dynamic size, maintain order, support multiple data types, efficient indexing and slicing                                                                           | Costly for large operations, linear time complexity for certain operations                                                                                                                                                                                                                                                | Managing collections, dynamic resizing, maintaining order                                              | `my_list = [1, 2, 3]`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Mutable          | Maintain     | Yes               | Moderate                     | Efficient with indexing and slicing                             | In-place sorting (`my_list.sort()`)                           | Linear                                             | High                                              | Elements can be modified |
| Tuple          | tuple           | Immutable sequence of elements          | Fixed-length array                 | Access, Slicing                                                 | Access: O(1)<br>Search: O(n)                                    | O(n)                              | Immutable, hashable, used as keys in dictionaries, represent fixed collections, multiple data types allowed                                                                     | Elements cannot be modified, need to create a new tuple to make changes                                                                                                                                                                                                                                                | Representing fixed collections, returning multiple values                                              | `my_tuple = (1, 2, 3)`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Immutable        | Maintain     | Yes               | Low                          | Efficient with indexing                                         | Sorted tuple (`sorted(my_tuple)`)                             | Linear                                             | High                                              | Elements cannot be modified |
| Set            | set             | Unordered collection of unique elements | Hash table or binary search tree  | Membership testing, Adding elements, Removing elements, Set operations (union, intersection, etc.)                           | Access: O(1)<br>Search: O(1)<br>Insertion: O(1)<br>Deletion: O(1) | O(n) (average)<br> O(n^2) (worst-case for hash table) | Unique elements, support set operations, fast membership testing, efficient removal of duplicates                                                                             | No indexing, unordered collection                                                                                                                                                                                                                                                                                   | Removing duplicates, membership testing, set operations                                                 | `my_set = {1, 2, 3}`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Mutable          | Unordered    | No                | Moderate                     | Efficient membership testing                                    | Not applicable                                                | Constant                                           | Moderate                                          | Elements can be modified |
| Dictionary     | dict            | Collection of key-value pairs           | Hash table                         | Access, Insertion, Deletion, Iteration                            | Access: O(1)<br>Search: O(1)<br>Insertion: O(1)<br>Deletion: O(1) | O(n) (average)<br> O(n^2) (worst-case)              | Fast key-value lookups, unordered collection, support various data types as keys and values, efficient insertion and deletion operations                                     | No ordering of elements                                                                                                                                                                                                                                                                                             | Key-value mapping, fast lookup, unordered storage                                                  | `my_dict = {'name': 'John', 'age': 25}`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Mutable          | Unordered    | Keys must be unique | High (key-value pairs)       | Efficient key-based lookup                                      | Not applicable                                                | Constant (average)<br> O(n) (worst-case)               | High                                              | Elements can be modified |
| String         | str             | Immutable sequence of characters        | Array of Unicode characters        | Access, Concatenation, Slicing                                   | Access: O(1)<br>Search: O(n)                                    | O(n)                              | Immutable, efficient string manipulation, support various string operations, memory-efficient storage                                                                         | Elements cannot be modified, need to create a new string to make changes                                                                                                                                                                                                                                              | Text processing, manipulation, pattern matching                                                       | `my_string = "Hello, World!"`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Immutable        | Maintain     | No                | Low                          | Efficient with indexing                                         | Sorted string (`''.join(sorted(my_string))`)                  | Linear                                             | High                                              | Elements cannot be modified |
| Deque          | deque           | Double-ended queue                      | Doubly-linked list                 | Access, Insertion, Deletion from both ends                       | Access: O(1)<br>Search: O(n)                                    | O(n)                              | Efficient enqueue and dequeue operations, support stack and queue operations, efficient insertion and deletion at both ends                                                     | No random access, slower than lists for indexed operations                                                                                                                                                                                                                                                           | Efficient enqueue and dequeue operations, double-ended queue                                          | `from collections import deque`<br>`my_deque = deque([1, 2, 3])`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Mutable          | Maintain     | Yes               | Moderate                     | Efficient enqueue and dequeue operations                         | In-place sorting (`my_deque.sort()`)                           | Linear                                             | High                                              | Elements can be modified |
| OrderedDict    | OrderedDict     | Ordered dictionary                      | Doubly-linked list and hash table | Access, Insertion, Deletion, Iteration                            | Access: O(1)<br>Search: O(n)                                    | O(n)                              | Ordered iteration, key insertion order is maintained                                                                                                                             | Slightly slower performance and higher memory usage compared to regular dictionaries                                                                                                                                                                                                                                | Preserving order of elements, ordered iteration                                                       | `from collections import OrderedDict`<br>`my_ordered_dict = OrderedDict([('name', 'John'), ('age', 25)])`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Mutable          | Maintain     | Keys must be unique | Moderate                     | Ordered iteration                                              | In-place sorting (`my_ordered_dict.sort()`)                    | Linear                                             | Moderate                                          | Elements can be modified |
| DefaultDict    | defaultdict     | Dictionary with default values          | Hash table                         | Access, Insertion, Deletion, Iteration                            | Access: O(1)<br>Search: O(n)                                    | O(n)                              | Providing default values for keys, counting occurrences                                                                                                                          | Slightly slower performance and higher memory usage compared to regular dictionaries                                                                                                                                                                                                                                | Providing default values for keys, counting occurrences                                              | `from collections import defaultdict`<br>`my_default_dict = defaultdict(int)`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Mutable          | Unordered    | Keys must be unique | Moderate                     | Default values for missing keys are provided                   | Not applicable                                                | Constant                                           | Moderate                                          | Elements can be modified |
| Counter        | Counter         | Counting occurrences of elements         | Hash table                         | Access, Insertion, Deletion, Iteration                            | Access: O(1)<br>Search: O(n)                                    | O(n)                              | Efficient element counting, support arithmetic and set operations                                                                                                               | Higher memory usage compared to regular dictionaries                                                                                                                                                                                                                                                               | Counting occurrences of elements                                                                     | `from collections import Counter`<br>`my_counter = Counter([1, 1, 2, 3, 3, 3])`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Mutable          | Unordered    | Yes               | High                         | Efficient counting operations                                   | In-place sorting (`my_counter.sort()`)                         | Linear                                             | Moderate                                          | Elements can be modified |
| Heap           | heapq           | Binary heap                             | Array or list                      | Heapify, Push, Pop, Peek, Merge, Heap sort                        | Access: O(1)<br>Search: O(n)                                    | O(n)                              | Finding minimum/maximum elements, priority queues, graph algorithms                                                                                                            | Not suitable for general-purpose indexing and search operations                                                                                                                                                                                                                                                     | Priority queues, finding minimum/maximum elements, graph algorithms                                 | `import heapq`<br>`my_heap = [3, 1, 2]`<br>`heapq.heapify(my_heap)`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Mutable          | No           | No                | Low                          | Efficient minimum/maximum element extraction                    | In-place sorting (`heapq.heapify(my_list)`)                    | Constant                                           | High                                              | Elements can be modified |
| Stack          | list            | Last-in, first-out (LIFO) structure      | Dynamic array                      | Push, Pop, Peek                                                 | Access: O(1)<br>Search: O(n)<br>Insertion: O(1)<br>Deletion: O(1) | O(n)                              | Efficient push and pop operations, support LIFO behavior                                                           | Slower performance compared to deque for enqueue and dequeue operations                                                                                                                                                                                                                                            | Managing function calls, expression evaluation, undo/redo operations                                 | `my_stack = []`<br>`my_stack.append(1)`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Mutable          | Maintain     | Yes               | Moderate                     | Efficient push and pop operations                               | In-place sorting (`my_stack.sort()`)                          | Linear                                             | High                                              | Elements can be modified |
| NamedTuple     | namedtuple      | Immutable, named tuple                  | Subclass of tuple                  | Access                                                          | Access: O(1)<br>Search: O(n)                                    | O(n)                              | Immutable, named fields for accessing elements                                                                      | Elements cannot be modified, need to create a new named tuple to make changes                                                                                                                                                                                                                                      | Representing lightweight immutable objects with named fields                                         | `from collections import namedtuple`<br>`MyTuple = namedtuple('MyTuple', ['name', 'age'])`<br>`my_tuple = MyTuple(name='John', age=25)`                                                                                                                                                                                                                                                                                                                                                                                                                      | Immutable        | Maintain     | Yes               | Low                          | Efficient with indexing                                         | Sorted named tuple (`sorted(my_tuple)`)                       | Linear                                             | High                                              | Elements cannot be modified |
