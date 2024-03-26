# Repository: alx-higher_level_programming

## 0x02-python-import_modules

This repository hosts solutions to several tasks involving Python import modules.

### Tasks:

1. **Import a simple function from a simple file**  
   - Program: `0-add.py`
   - Description: Import the function `add(a, b)` from the file `add_0.py` and print the result of the addition `1 + 2 = 3`.
   - Instructions: Refer to the program for detailed instructions.
   - Example:
     ```
     $ ./0-add.py
     1 + 2 = 3
     ```

2. **My first toolbox!**
   - Program: `1-calculation.py`
   - Description: Import functions from `calculator_1.py`, perform mathematical operations, and print the results.
   - Instructions: Refer to the program for detailed instructions.
   - Example:
     ```
     $ ./1-calculation.py
     10 + 5 = 15
     10 - 5 = 5
     10 * 5 = 50
     10 / 5 = 2
     ```

3. **How to make a script dynamic!**
   - Program: `2-args.py`
   - Description: Print the number and list of arguments passed to the script.
   - Instructions: Refer to the program for detailed instructions.
   - Example:
     ```
     $ ./2-args.py
     0 arguments.
     $ ./2-args.py Hello
     1 argument:
     1: Hello
     $ ./2-args.py Hello Welcome To The Best School
     6 arguments:
     1: Hello
     2: Welcome
     3: To
     4: The
     5: Best
     6: School
     ```

4. **Infinite addition**
   - Program: `3-infinite_add.py`
   - Description: Print the result of the addition of all arguments passed to the script.
   - Instructions: Refer to the program for detailed instructions.
   - Example:
     ```
     $ ./3-infinite_add.py
     0
     $ ./3-infinite_add.py 79 10
     89
     $ ./3-infinite_add.py 79 10 -40 -300 89 
     -162
     ```

5. **Who are you?**
   - Program: `4-hidden_discovery.py`
   - Description: Print all names defined in the compiled module `hidden_4.pyc`.
   - Instructions: Refer to the program for detailed instructions.
   - Example:
     ```
     $ curl -Lso "hidden_4.pyc" "https://github.com/alx-tools/0x02.py/raw/master/hidden_4.pyc"
     $ ./4-hidden_discovery.py | sort
     my_secret_santa
     print_hidden
     print_school
     ```

6. **Everything can be imported**
   - Program: `5-variable_load.py`
   - Description: Import the variable `a` from the file `variable_load_5.py` and print its value.
   - Instructions: Refer to the program for detailed instructions.
   - Example:
     ```
     $ ./5-variable_load.py
     98
     ```

**Note:** Each program comes with specific instructions outlined in the comments or the task description.

For more details about each task, please refer to the individual program files in this directory.