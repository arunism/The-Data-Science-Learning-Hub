# Exception Handling

Exceptions are errors that occur during program execution. Besides exceptions, Python suffers from other types of errors as well. Let's go through a brief overview of those errors.

- `Syntax errors`: These errors occur when the code is not written in the correct syntax or structure expected by Python. These errors are caught by the interpreter during the compilation of the code.
- `Runtime errors`: These errors occur during the execution of the program, when the program is unable to execute a specific instruction or operation. These errors are also known as exceptions.
- `Logical errors`: These errors occur when the program runs without any syntax or runtime errors, but the output is not what was expected. These errors are caused due to incorrect or incomplete logic in the program.

Exceptions cause the program to stop abruptly, and it can be challenging to identify and fix the issue without proper error handling. To address these issues, Python has a built-in exception handling mechanism that allows you to catch, handle, and recover from exceptions.

## Types of Exceptions in Python

### 1. Built-in Exceptions

Python has several built-in exceptions. Each of these exceptions is raised when a specific error occurs in the program.

- `SyntaxError`: Raised when there is a syntax error in the program
- `TypeError`: Raised when an operation or function is applied to an object of inappropriate type
- `ValueError`: Raised when an operation or function receives an argument of the correct type but with an inappropriate value
- `IndexError`: Raised when trying to access an index that is out of range
- `KeyError`: Raised when trying to access a key that does not exist in a dictionary
- `AttributeError`: Raised when trying to access an attribute that does not exist in an object
- `NameError`: Raised when a variable or name is not defined
- `IOError`: Raised when there is an input/output error
- `ImportError`: Raised when a module cannot be imported
- `KeyboardInterrupt`: Raised when the user interrupts the execution of the program with a keyboard signal (Ctrl+C)

### 2. User-defined Exceptions

In addition to built-in exceptions, Python allows you to define your own exceptions. User-defined exceptions are used to signal specific errors in the program that are not covered by built-in exceptions.
