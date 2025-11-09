// What do you mean by Structures?
// Answer
#include <stdio.h>

struct Student {
    int roll;
    char name[50];
    float marks;
};

int main() {
    struct Student s = {1, "Virat", 95.5};
    printf("%d %s %.2f", s.roll, s.name, s.marks);
    return 0;
}
// output 
1 Virat 95.50
// What do you mean by array and pointer array?
// Answer
#include <stdio.h>

int main() {
    int a[3] = {10, 20, 30};
    int *p[3] = {a, a+1, a+2};

    printf("%d %d %d\n", a[0], a[1], a[2]);
    printf("%d %d %d", *p[0], *p[1], *p[2]);

    return 0;
}
// Output
10 20 30
10 20 30
//compare two structures variables by using the comparison operator (not equal and equal)
// Answer
#include <stdio.h>
#include <string.h>

struct Student {
    int roll;
    char name[20];
};

int main() {
    struct Student s1 = {1, "Virat"}, s2 = {1, "Virat"};

    if (s1.roll == s2.roll && strcmp(s1.name, s2.name) == 0)
        printf("Equal");
    else
        printf("Not Equal");

    return 0;
}
//Output
Equal
//perform an arithmetic operations on structures
//Answer
#include <stdio.h>

struct Numbers {
    int a, b;
};

int main() {
    struct Numbers n = {10, 5};
    printf("Addition = %d\n", n.a + n.b);
    printf("Subtraction = %d\n", n.a - n.b);
    printf("Multiplication = %d\n", n.a * n.b);
    printf("Division = %d\n", n.a / n.b);
    return 0;
}
// Output
Addition = 15
Subtraction = 5
Multiplication = 50
Division = 2
