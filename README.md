## Hi, I'm DrMaddMam (aka Fanta)  
## Check out my epic library  
## [MaddHack](https://github.com/DrMaddMam/MaddHack)  
# I make dohickeys in:  
* C  
* C++  
* C# (kinda)  
* and Asssembly  
---
# My Code formatting
## Curly Bracket Placement
Put curly brackets in the same line as a function/struct
```
void main() {
    printf("Hello, World!\n");
}
```
## Tab size/Spaces
Use spaces because if you want to edit your code somewhere else there is a varible tab size from 2-4-8
Use 4 spaces for indents
```
void main() {
    if (4 < 5) {
        if (6 < 9) {
            printf("Math works!\n");
        }
    }
}
```
## () Placement
For functions use function() for everything else use if ()
```
void main() {
    for (int i = 0; i < 100; ++i) {
        printf("%d\n",i);
    }
}
```
## i++ or ++i
Use ++i because it is faster, most compilers do that automatically but some might not, so it is good practice to do so.
```
int strlen(char* str) {
    int i = 0;
    while (str[i]) {
        ++i;
    }
    return i;
}
```
## * Pointer placement
Where I put * for pointers is based on whether it's obvious it's a pointer, if it isn't obvious put it before the name as if it were part of the name
```
int num = 4;
int *ptr = &num;
```
If it is obvious, like in a string ptr, I put it as if it were the type
```
void putStr(char* str) {
    while (*str) {
        putchar(*(++str));
    }
}
```
