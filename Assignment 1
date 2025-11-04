# C-programming

🧮 1. What do you mean by Arrays? Give one example of array and how you can declare an array.

Definition:

An Array is a collection of elements of the same data type stored in contiguous (continuous) memory locations.
Each element of the array can be accessed using an index.

Syntax:

data_type array_name[size];

Example:

#include <stdio.h>
int main() {
    int numbers[5] = {10, 20, 30, 40, 50}; // Declaration and Initialization
    printf("First element: %d\n", numbers[0]);
    printf("Third element: %d\n", numbers[2]);
    return 0;
}


---

🧩 2. What do you mean by Functions? Write the types of functions and give one example in code of each type.

Definition:

A function is a block of code that performs a specific task and can be called multiple times in a program.

Types of Functions:

1. Library Functions – Predefined functions (e.g., printf(), scanf(), sqrt()).


2. User-defined Functions – Functions created by the user.



Example (User-defined Function):

(a) Function with No Argument and No Return Value:

#include <stdio.h>
void greet() {       // Function Definition
    printf("Hello, World!\n");
}
int main() {
    greet();         // Function Call
    return 0;
}

(b) Function with Argument and Return Value:

#include <stdio.h>
int add(int a, int b) {   // Function with arguments
    return a + b;
}
int main() {
    int result = add(5, 3);
    printf("Sum = %d\n", result);
    return 0;
}


---

🎯 3. What do you mean by Pointers? Write a code how you can initialize the pointer.

Definition:

A Pointer is a variable that stores the memory address of another variable.

Syntax:

data_type *pointer_name;

Example:

#include <stdio.h>
int main() {
    int x = 10;
    int *ptr;       // Pointer declaration
    ptr = &x;       // Pointer initialization
    printf("Value of x: %d\n", x);
    printf("Address of x: %p\n", &x);
    printf("Value stored in pointer: %p\n", ptr);
    printf("Value pointed by pointer: %d\n", *ptr);
    return 0;
}


---

🧠 4. What are the types of Arrays? Write code for 1D & 2D Array.

Types of Arrays:

1. One Dimensional Array (1D)


2. Two Dimensional Array (2D)


3. Multidimensional Array



Example (1D Array):

#include <stdio.h>
int main() {
    int marks[5] = {50, 60, 70, 80, 90};
    for(int i = 0; i < 5; i++) {
        printf("marks[%d] = %d\n", i, marks[i]);
    }
    return 0;
}

Example (2D Array):

#include <stdio.h>
int main() {
    int matrix[2][3] = {{1,2,3}, {4,5,6}};
    for(int i = 0; i < 2; i++) {
        for(int j = 0; j < 3; j++) {
            printf("%d ", matrix[i][j]);
        }
        printf("\n");
    }
    return 0;
}


---

⚙️ 5. Explain the types of Operators in code.

Types of Operators in C:

1. Arithmetic Operators → +, -, *, /, %


2. Relational Operators → ==, !=, <, >, <=, >=


3. Logical Operators → &&, ||, !


4. Assignment Operators → =, +=, -=, *=, /=


5. Increment/Decrement Operators → ++, --


6. Conditional (Ternary) Operator → ? :


7. Bitwise Operators → &, |, ^, <<, >>



Example:

#include <stdio.h>
int main() {
    int a = 10, b = 5;
    printf("Addition: %d\n", a + b);         // Arithmetic
    printf("Is a > b? %d\n", a > b);         // Relational
    printf("Logical AND: %d\n", (a > 0 && b > 0));  // Logical
    a += 2;                                  // Assignment
    printf("After += : %d\n", a);
    printf("Ternary: %s\n", (a > b) ? "a is greater" : "b is greater");
    return 0;
}
