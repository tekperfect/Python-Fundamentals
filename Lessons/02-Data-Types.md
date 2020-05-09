# 📈 Day 2: Data Types

### ⏱ Agenda

1. [🏆 Learning Objectives](#%f0%9f%8f%86-learning-objectives)
1. [📖 What are Data Types](#%f0%9f%93%96-what-are-data-types)
1. [📊 Data Types](#%f0%9f%93%8a-data-types)
1. [🐍 REPL - Try It Yourself!](#%f0%9f%90%8d-repl-try-it-yourself)
1. [📚 Resources & Credits](#%f0%9f%93%9a-resources-amp-credits)

## 🏆 Learning Objectives

**By the end of this, you'll be able to...**

1. Understand how to create and use variables
2. Undestand what different Data Types there are
3. What data type is best for what
4. Best pratise for data types

## 📖 What are Data Types?

Data types are the classification or categorization of data items. Data types represent a kind of value which determines what operations can be performed on that data. The most basic types can be classifed under as Numeric, Sequence, Boolean and Dictionary

> tl;dr : Data types classify and represent what something is and what you can do with them

> Remember try it yourself in the REPL


## 📊 Data Types
### Numeric
A Numeric value is any data represented as a Numeral:

**Intiger:** Positive or negative _whole numbers_.
```python
int = 123
```

**Float:** Any real number denoted with a _decimal or scientific notation_.
```python
float = 123.001
```

### Sequence

A sequence is a collection of the same or different data types: 

**List:** A string value is a collection of one or more characters, put in _s_quare brackets_.
```python
list = [1,2,3,4,5]
list2 = ["Ninja", "Alfonso", "Holy Grail", 21] 
```

**Tuple:** A Tuple object is an ordered collection of one or more data items, put in _parentheses_. 
```python
tuple = (1,2,3,4,5)
tuple2 = ("Ninja", "Alfonso", "Holy Grail", 21)
``` 

**String:**  A Tuple object is an ordered collection of one or more data items, _single, double or triple quotes_.
```python
Dog = "Ninja's German Shephard"
Person = 'Ninja\' German Shephard' # Note the escape character because they are not the same closing character
Alfonso = """
Ninja
Alfonso
Dog
"""
```

### Boolean
A data type of either value `True` or `False`. _note the capitilization_
```python
True
False
true
false
```

### Dictionary
Collection of data in a key:value pair form, put in _curly brackets_
```python
seus = {'fish': 3, 'red': 1, 'blue': 1, 'green': 1}
```


## 🐍 REPL - Try It Yourself!
Python has a built-in function called type() to find out what type of data it is. Try it yourself with these:

```python
question1 = "True"
```

```python
question2 = False
```

```python
question3 = """
1234
"""
```

```python
question4 = "{"Dog": 3}"
```

```python
question5 = ["Alfonso", 123, 'ninja', True]
```

```python
question6 = 123.04
```

```python
question7 = {"Dog": 200}
```
## 📚 Resources & Credits
- [W3Schools](https://www.w3schools.com/python/python_datatypes.asp)