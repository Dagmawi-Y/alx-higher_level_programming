# 0x0A. Python - Inheritance

This project contains tasks related to inheritance in Python, focusing on how to define classes, manage methods, and explore inheritance patterns. It is part of the ALX Software Engineering curriculum.

## Files

### Mandatory Tasks

- **[0-lookup.py](./0-lookup.py)**: A function that returns the list of available attributes and methods of an object.
- **[1-my_list.py](./1-my_list.py)**: A class `MyList` that inherits from `list` and has a method `print_sorted()` to print the list sorted.
- **[2-is_same_class.py](./2-is_same_class.py)**: A function that returns True if an object is exactly an instance of a specified class, otherwise False.
- **[3-is_kind_of_class.py](./3-is_kind_of_class.py)**: A function that returns True if an object is an instance of a specified class or if it inherits from the class.
- **[4-inherits_from.py](./4-inherits_from.py)**: A function that returns True if an object inherits directly or indirectly from a specified class, otherwise False.
- **[5-base_geometry.py](./5-base_geometry.py)**: An empty class `BaseGeometry`.
- **[6-base_geometry.py](./6-base_geometry.py)**: A class `BaseGeometry` with a method `area()` that raises an exception stating it is not implemented.
- **[7-base_geometry.py](./7-base_geometry.py)**: Extends `BaseGeometry` with a method `integer_validator()` that validates an integer input.
- **[8-rectangle.py](./8-rectangle.py)**: A class `Rectangle` that inherits from `BaseGeometry` and initializes with width and height.
- **[9-rectangle.py](./9-rectangle.py)**: A class `Rectangle` that extends `BaseGeometry` with a method to calculate area and a custom representation.
- **[10-square.py](./10-square.py)**: A class `Square` that inherits from `Rectangle` and initializes with a size attribute.
- **[11-square.py](./11-square.py)**: A class `Square` that extends `Rectangle` with a method to calculate area and a custom representation.

### Advanced Tasks

- **[100-my_int.py](./100-my_int.py)**: A class `MyInt` that inherits from `int` and inverts the `==` and `!=` operators.
- **[101-add_attribute.py](./101-add_attribute.py)**: A function that adds a new attribute to an object if possible, otherwise raises a `TypeError`.

## Testing

- The repository includes a directory called `tests` that contains test cases for some of the tasks.
- To execute the tests, use the command: `python3 -m doctest ./tests/*`
- Proper documentation and comments should be added to the code to explain the modules, classes, and methods.

## Author

Dagmawi Y.
