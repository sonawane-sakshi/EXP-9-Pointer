# Pointer Basics
Experiment 9

## Aim 
To study and implement Basic of Pointers.

## Theory
**Definition**
<br>
A pointer is a variable that stores the memory address of another variable. It does not hold any actual data value like a normal variable, instead holds the location where the data is stored in memory. Pointers allow for efficient array and memory management, and can be used to directly manipulate memory.
The basic syntax to define a pointer is:
```cpp
int a = 10;
int *ptr = &a;
```
<br>  

*Visual Representation of memory address:*
<br>

| Address | Contents     |
|---------|--------------|
| 0x8130  | 0x00000005   |
| 0x8134  | 0x00000000   |

<br>
  
**Features of Pointers**  
- An array, of any type, can be accessed with the help of pointers, without considering its subscript range.
- Pointers are used for file handling.
- Pointers are used to allocate memory dynamically.

**Advantages of Pointers**
- Memory efficiency: Pointers allow for memory-efficient data sharing between different parts of a program. 
- Improved performance: Pointers can help reduce code and improve program performance. 
- Multiple values: Pointers allow programmers to return multiple values from a function. 
- Data structure building: Pointers can be used to build complex data structures like linked lists, trees, and graphs

**Drawbacks of Pointers**
- It requires one additional dereferences step 
- If we forgot to deallocate a memory then it will lead to a memory leak. 

## Algorithms
### Address of Data Type after Increment

1.  **Start**
2. **Initialize Variables**
   - Define an integer variable `a` with value 10.
   - Define a pointer variable `ptr` of type `int*` and set it to point to `a`.
   - Define a float variable `b` with value 9.4.
   - Define a pointer variable `fptr` of type `float*` and set it to point to `b`.
   - Define a char variable `c` with value 's'.
   - Define a pointer variable `cptr` of type `char*` and set it to point to `c`.
   - Define a bool variable `d` with value `1` (true).
   - Define a pointer variable `dptr` of type `bool*` and set it to point to `d`.

4. **Integer Pointer Operations**
   - Print "For integer".
   - Print "Before increment".
   - Print the address stored in `ptr` (address of `a`).
   - Increment `ptr` (move to the next integer address).
   - Print "After increment".
   - Print the new address stored in `ptr`.

5. **Float Pointer Operations**
   - Print"For float".
   - Print "Before increment".
   - Print the address stored in `fptr`.
   - Increment `fptr`.
   - Print "After increment".
   - Print the new address stored in `fptr`.

6. **Boolean Pointer Operations**
   - Print"For boolean".
   - Print "Before increment".
   - Print the address stored in `dptr`.
   - Increment `dptr`.
   - Print "After increment".
   - Print the new address stored in `dptr`.

7. **Character Pointer Operations**
   - Print "For character".
   - Print "Before increment".
   - Print the address stored in `cptr`.
   - Increment `cptr`.
   - Print "After increment".
   - Print the new address stored in `cptr`.
8. **End**
