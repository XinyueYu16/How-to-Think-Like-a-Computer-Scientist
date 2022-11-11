# How-to-Think-Like-a-Computer-Scientist
Reading notes of _How to Think Like a Computer Scientist_

## 6. Fruitful functions
- **increamental development**:  avoid long debugging sessions by adding and testing only a small amount of code at a time.
  - develop a function bit by bit, test by test
  - *build the bone, add the meat, see how to make it tastier*

- **PEP8 style guide**:
  ```
  - use 4 spaces (instead of tabs) for indentation
  - limit line length to 78 characters
  - when naming identifiers, use CamelCase for classes (we’ll get to those) and lowercase_with_underscores for functons and variables
  - place imports at the top of the file
  - keep function definitions together
  - use docstrings to document functions
  - use two blank lines to separate function definitions from each other
  - keep top level statements, including function calls, together at the bottom of the program
  ```
  
  - **unit testing**:
    - Automatically verify that individual pieces of code, such as functions, are working properly.
    - Programmers need to take into all kinds of data types/contents into consideration.
    - Usually use Pytest, assert ...
    
