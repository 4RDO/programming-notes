# C++ Structures

## What are Structures?
* Structures (struct) are a way to group different data types into one location.


## Key Concepts
* Each variable in a struct is known as a **member**
* Can contain different data types
* The dot operator (.) is used to access and assign values to members
* After the end of the definition struct {}, there is an optional field which is used to declare objects.


## Code Example
```cpp
struct car {    // Declares struct type called car
    string title;   // Member with string data type
    int year;   // Member with int data type
} tesla;    // Tesla object declared

int main() {
    tesla.title = "Model Y";    // accessing member and assigning variable
    tesla.year = 2024;
}