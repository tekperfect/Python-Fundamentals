# 📜 Day 1: Getting Started

> _Python: Short, Concise, Beautiful and Readable._

### ⏱ Agenda

1. [🏆 Learning Objectives](#%f0%9f%8f%86-learning-objectives)
1. [📖 Discovering Python](#%f0%9f%93%96-discovering-python)
1. [🐍 REPL - Python Interactive Shell](#%f0%9f%90%8d-repl-python-interactive-shell)
1. [✏️ Python Syntax](#%e2%9c%8f%ef%b8%8f-python-syntax)
1. [📚 Resources & Credits](#%f0%9f%93%9a-resources-amp-credits)

## 🏆 Learning Objectives

**By the end of this, you'll be able to...**

1. Understand how to run pythons shell and .py files
2. Introduce python language

## 📖 Discovering Python

### Why Use Python?

1. Python is a general purpose language
2. resence of Third Party Modules
3. Extensive Support Libraries
4. Most importantly it's readable!

### Installing Python

```shell
# If you don't have brew or any other package manager please refer to the Tekperfect: Setup
brew install python
```
### Running Any Python Program

All ```.py``` extensions is a python file

```shell
python example.py # python3 or python2 works for version specific files
hello world
```

## 🐍 REPL - Python Interactive Shell

What is REPL? REPL is the language shell, the Python Interactive Shell. The REPL acronym is short for **Read**, **Eval**, **Print** and **Loop**.

The Python interactive interpreter can be used to easily check Python[2,3] commands. To start the Python interpreter, type the command python without any ```parameter``` and hit the “return” key in terminal.

```shell
python3

Python 3.7.7 (default, Mar 10 2020, 15:43:03) 
[Clang 11.0.0 (clang-1100.0.33.17)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

you can do anything in the shell that is a valid line of code or object, such as strings

```python
# Python REPL
>>> "hello world"
'hello world'
```

Math: 
```python
# Python REPL
>>> 10/5
2
```

or variables:
```python
# Python REPL
>>> dog = "Golden Retriever"
>>> dog 
'Golden Retriever'
```
> _to clear try ```crtl-L```_

to exit the REPL ```crtl-D``` or exit() 

```python
# Python REPL
>>> exit()
```
## ✏️ Python Syntax

python ignores blank lines and pays special attention to indentation(4 spaces or a tab) and most variables names are in lower_case_with_underscores. 

Otherwise python is very lenient on structure: 
```python
days = ['Monday', 'Tuesday', 'Wednesday',
        'Thursday', 'Friday']
```

indentation Error:
```python
if True:
print "Answer"
print "True"
else:
print "Answer"
print "False"
```

```python
if True:
   print "True"
else:
   print "False"
```
For more information refer to 📚 Resources & Credits
## 📚 Resources & Credits

- [Basic Syntax](https://www.tutorialspoint.com/python/python_basic_syntax.htm)
- [Python Documentation](https://docs.python.org/3/)
- [PEP8 Conventions](https://www.python.org/dev/peps/pep-0008/)
