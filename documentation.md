# InVesalius - Mypy Integration

This is a guide on how to use Mypy to check for type errors in the InVesalius codebase.

## Prerequisites

To use Mypy, you will need to have Python 3.5 or later installed on your system.

## Installation

1.  Clone the InVesalius repository:

bashCopy code

`git clone https://github.com/invesalius/invesalius.git` 

2.  Install the required dependencies:

bashCopy code

`pip install -r requirements.txt` 

3.  Install Mypy:

bashCopy code

`pip install mypy` 

## Running Mypy

To run Mypy on the InVesalius codebase, navigate to the root directory of the project and run:

bashCopy code

`mypy .` 

This will check all Python files in the directory for type errors.

## Interpreting Mypy Output

When Mypy runs, it will output any type errors it finds. Each error message includes the file and line number where the error occurred, as well as a description of the error.

For example:

goCopy code

`app.py:5: error: Argument 1 to "print_greeting" has incompatible type "int"; expected "str"` 

This error occurred in the `app.py` file, on line 5. It indicates that the `print_greeting` function was called with an `int` argument, but it expects a `str` argument.

## Conclusion

By using Mypy to check for type errors in the InVesalius codebase, you can improve the code quality and maintainability of the project. If you encounter any issues while using Mypy, please refer to the [official Mypy documentation](https://mypy.readthedocs.io/en/stable/).
