# Tokenization
Using Python re library for tokenization and AST library for syntax tree.
Using Re-Library of python.
can also use the re (regular expression) module to tokenize an expression. The re module provides a set of functions for working with regular expressions, which are patterns that can be used to match and extract strings
To use the re module, you will first need to import it using the following import statement:
*import re*.
 Then, you can use the re.findall function to find all the tokens in an expression. This function takes a regular expression pattern as its first argument and a string to search as its second argument and returns a list of all the matches. 
 The regular expression r".\(\)\*\w+ “specifies that we want to match any sequence of words ,digits or under score  (\w+), or the asterisk (\*) etc.
 # SYNTAX TREE
 Implementation of syntax tree using AST library of python
The ast (abstract syntax tree) module in Python provides tools for parsing and analyzing Python source code. One of the main features of the ast module is the ability to create an abstract syntax tree (AST) from a string of Python code.

An abstract syntax tree is a tree-like representation of the structure of a Python program. It shows the relationships between different elements of the code, such as variables, operators, and function calls.

To use the ast module, you will first need to import it using the following import statement:

import ast

Then, you can use the ast.parse function to create an AST from a string of Python code. This function takes a string of Python code as input and returns an AST object, which represents the root node of the abstract syntax tree
