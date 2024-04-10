# Test-Driven Development in Python

This repository provides Python scripts and their corresponding test cases to help you practice test-driven development (TDD) in Python.

## Description

TDD is a software development approach where you write tests before writing the actual code. This ensures that the code you write meets the intended functionality from the beginning.

## Files

The repository includes the following files:

* **Python Scripts:**
    - `0-add_integer.py`: Script to add two integers.
    - `2-matrix_divided.py`: Script to divide all elements of a matrix.
    - `3-say_my_name.py`: Script to print a person's name.
    - `4-print_square.py`: Script to print a square using "#" characters.
    - `5-text_indentation.py`: Script to print text with new lines after specific characters.
    - `6-max_integer.py`: Script to find the maximum integer in a list.
    - `100-matrix_mul.py`: Script to multiply two matrices.
    - `101-lazy_matrix_mul.py`: Script to multiply two matrices using NumPy.
    - `102-python.c`: C file containing a function to print Python strings.
* **Test Cases:**
    - `tests/`: Directory containing test cases for the Python scripts.
* **Documentation:**
    - `README.md`: This file (current file) explaining the repository structure and usage.

## Usage

**Executing Scripts**

Use the following command in your terminal to execute a script:

```bash
./script_name.py

## Running Tests

Navigate to the `tests/` directory using your terminal. Then, use the following command to run the tests for a specific test file:

```bash
python3 -m doctest -v test_file.txt