
# Python Naming Conventions

## 1. Naming Python Script Files (Scripts):
- **Lowercase and underscores**: Python script names should be written in lowercase and use underscores (`_`) to separate words if the name consists of multiple words.
  - Example: `my_script.py`, `data_processing.py`

- **Avoid special characters**: File names should only include letters, numbers, and underscores. Special characters like spaces, dashes, or others should not be used.
  - Invalid example: `my-script.py`, `data processing.py`

- **Clear and descriptive names**: The script name should clearly describe its functionality. This helps others understand the purpose of the file without needing to open it.
  - Example: `process_data.py` is better than `script1.py`.

## 2. Naming Variables, Functions, and Classes:

### Variables and Functions:
- **Lowercase and underscores**: Use lowercase letters and underscores to separate words when naming variables and functions.
  - Example: `user_name`, `calculate_total()`

- **Meaningful names**: Variable and function names should be meaningful, describing their purpose or the data they represent.
  - Example: `age`, `calculate_sum()` is better than `x`, `func1()`

- **Avoid Python keywords**: Do not use Python reserved keywords (like `class`, `def`, `if`, `else`, etc.) as names.

### Classes:
- **CamelCase (PascalCase)**: Class names should follow **PascalCase** (capitalize the first letter of each word, without underscores).
  - Example: `MyClass`, `DataProcessor`

## 3. PEP 8 Community Guidelines:
- **PEP 8** is a document that provides coding style guidelines for Python. According to PEP 8, some important naming rules include:
  - **Variables and functions**: Use lowercase letters with underscores between words.
  - **Classes**: Use PascalCase for class names.
  - **Constants**: Use all uppercase letters with underscores between words (e.g., `MAX_SIZE`, `DEFAULT_TIMEOUT`).

## 4. Naming Modules and Packages:
- **Modules**: A Python file (.py) is called a module. The module name should follow the lowercase and underscore rule (similar to file names).
  - Example: `my_module.py`

- **Packages**: A package is a directory containing modules. Package names should be lowercase and without underscores unless necessary for clarity.
  - Example: `mypackage`, `datahandler`

## 5. Additional Rules:
- **Avoid short, unclear variable names**: Using names like `x`, `y`, or `a1` is only acceptable when they are temporary variables or have a clear meaning in context. Variable, function, and class names should be long enough to convey their meaning.
  
- **Avoid name conflicts with standard libraries**: Avoid naming variables, functions, or files with the same name as modules from the Python standard library (e.g., `string.py`, `os.py`), as this can cause conflicts.

## Example of Naming Conventions:
```python
# File name: user_data_handler.py

# Class definition using PascalCase
class UserDataHandler:
    def __init__(self, user_name):
        self.user_name = user_name  # Variable named in snake_case
    
    # Function named in snake_case
    def process_user_data(self):
        # Use variable names that are meaningful
        processed_data = f"Processed data for {self.user_name}"
        return processed_data

# Constant name in all caps
MAX_RETRIES = 5
```

Following these guidelines and conventions will help ensure that your code is readable, maintainable, and consistent with Python community standards.
