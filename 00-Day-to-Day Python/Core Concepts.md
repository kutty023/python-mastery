# 1. Variables and Data Types

## Variables 
- A variable is a named storage location in memory that holds data. It allows us to store, modify, and retrieve values during program execution.
- Variables are used for : 
    - ***Data storage*** - helps to store values that a program can use later.
    - ***Code Reusability*** - Instead of writing the same value multiple times, we store it in a variable.
    - ***Dynamic computing*** - We can change a variable's value and perform calculations.  
    - ***Memory Management*** - Variables efficiently manage memory allocation.
- Variables are used for storing numbers for arithmetic operations, controlling iterations, passing and returning values, store user input or decision making values, storing lists, dictionaries, objects, etc..,

<!--assigning variables  -->
###     Python example
```python
        x = 10
        name = "Joe"
        print(name+"is"+ str(x)+"years old")
```

###     C++ example
```cpp
        #include <iostream>
        using namespace std;
        int main(){
            int x = 10;
            string name = "Joe";
            cout << name << "is" << x << "years old";
            return 0;
        }
```
## Data Types
A data type defines the kind of value a variable can hold and how the computer should interpret that value.

### Python 
    It is a dynamically typed language, which indicates there is no need of declaring the variables type explicitly. the type is inferred automatically 

#### 1. Numeric types
    | Data Types  | Description          | example |
    | :---------- | :------------------: | :-----: |
    | int         | Stores whole numbers | x = 10  |
    | float       |	Stores decimal numbers | pi = 3.142|
    | complex     |	Stores complex numbers| z = 2 + 89 |
#### 2. Sequence Types
    | Data Types  | Description | example |
    | :---------- | :---------: | :-----: |
    | str| Stores text| name = "Joe" |
    | list | Ordered, mutable collection | arr = [1, 2, 3] |
    | tuple | Ordered, immutable collection | t = (1, 2, 3)|
#### 3. Set Types
    | Data Types  | Description | example |
    | :---------- | :---------: | :-----: |
    | set |	Unordered collection with unique elements | s = {1, 2, 3} |
    | frozenset | Immutable version of a set | fs = frozenset({1, 2,3}) |
#### 4. Mapping Type
    | Data Types  | Description | example |
    | :---------- | :---------: | :-----: |
    | dict | Stores key-value pairs| d = {"name":"Joe", "age" : 10} |
#### 5. Boolean Type
    | Data Types  | Description | example |
    | :---------- | :---------: | :-----: |
    | bool | Represents True or False | status = True |
#### 6. Binary Types
    | Data Types  | Description | example |
    | :---------- | :---------: | :-----: |
    | bytes	| Immutable byte sequence | b = b"hello" |
    | bytearray	| Mutable byte sequence	| ba = bytearray(5) |
    | memoryview | View of byte data | mv = memoryview(bytes(5)) |
#### 7. None type
    | Data Types  | Description | example |
    | :---------- | :---------: | :-----: |
    | NoneType | Represents absence of a value | x = None |

###     Python example
```python
        x = 10
        print(type(x))
```