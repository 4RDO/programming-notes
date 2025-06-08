# Create your first program using c++

## What is hello world used for?
The **hello world** is used to test setup and understand basic syntax

## Key Concepts
* A **header file** lets a compiler know what functions and objects are available
* #include < iostream > lets us works with input and output streams 
* cout is used in order to display text.
* The int main() is a function that is used for executing a program's instructions
* In C++, every statement/line ends with a semicolon ';'.
---

## code example: 
```cp
#include <iostream> // input-output library
using namespace std;    // allows for easier access to cout

int main() {
    // With namespace std;
    cout << "Hello World" << endl;  // Prints text to console
    return 0; // ends the program

    // Without namespace std;
    std::cout << "Hello World" << std::endl;  // Prints text to console
    return 0; // ends the program
}
