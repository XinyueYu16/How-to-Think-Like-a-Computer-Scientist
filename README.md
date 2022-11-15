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

## 11. List
- **Reference**
  - *Difference between mutables and immutables*
    - For immutable objects (strings and tuples), same contents === same object
    - For mutable objects (lists, dictionaries, modules...), same contents != same object
  - *Reference*
    - If you assign a to b, Changing part of mutable a will also leads to changing b
    - But if you reassign a's value, b would stay the same
  - *Modifier and Pure Functions*
    - Generally, always create pure functions that do not have side effects
    - When mutables used as function params, they could be modified in global space
    - If you want to explicitly edit any global variable (like state changing function), use *global* 
    
- **Difference of List and Range**: **Promise**
  - [1, 2, 3] and range(4) are different, asin the list will immediately take all the space the contents need, yet 'range' only gives a promise -- the space would only be taken up when the due content is required.
  - Similar promises: iterator, ...
