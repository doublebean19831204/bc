# bc - Basic Calculator

A simple Python calculator module with basic arithmetic operations and comprehensive test coverage.

## Features

- Addition
- Subtraction
- Multiplication
- Division (with zero-division protection)

## Usage

```python
from calculator import add, subtract, multiply, divide

result = add(5, 3)        # Returns 8
result = subtract(10, 4)  # Returns 6
result = multiply(3, 4)   # Returns 12
result = divide(10, 2)    # Returns 5.0
```

## Running Tests

Run all tests using Python's built-in unittest framework:

```bash
python -m unittest test_calculator.py -v
```

Or run tests without verbose output:

```bash
python -m unittest test_calculator.py
```

## Test Coverage

The test suite includes:
- Basic arithmetic operations tests
- Edge cases (negative numbers, zero)
- Error handling (division by zero)