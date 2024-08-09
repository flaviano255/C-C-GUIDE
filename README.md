# C++ C# GUIDE

![image alt](https://github.com/flaviano255/C-C-GUIDE/blob/ff2c1f6c9dea0326ec08a1252f931d8e6c2a38b9/giphy%20(1).webp)

Basics
 
1. Syntax and Structure:
 
-  #include <iostream> 
-  int main() { std::cout << "Hello, World!"; return 0; }

2. Variables and Data Types:
 
-  int, float, double, char, bool

3. Control Structures:
 
-  if, else, switch 
-  for, while, do-while

4. Functions:
 
- Declaration and definition
- Function overloading
- Inline functions

5. Pointers and References:
 
- Pointer arithmetic
- References vs. pointers

6. Object-Oriented Programming:
 
- Classes and objects
- Inheritance
- Polymorphism
- Encapsulation
 
7. Standard Template Library (STL):
 
- Vectors, Lists, Maps
- Iterators
- Algorithms (sort, find, etc.)
 
8. File I/O:
 
- Reading and writing files using  fstream 
 
Example Code 

```Cpp
#include <iostream>
#include <vector>
#include <algorithm>

int main() {
    std::vector<int> numbers = {1, 2, 3, 4, 5};
    std::sort(numbers.begin(), numbers.end());
    for (int num : numbers) {
        std::cout << num << " ";
    }
    return 0;
}
```

C## Guide

 
Basics
 
1. Syntax and Structure:
 
-  using System; 
-  class Program { static void Main() { Console.WriteLine("Hello, World!"); } }

2. Variables and Data Types:
 
-  int, float, double, char, bool, string
 
3. Control Structures:
 
-  if, else, switch 
-  for, while, do-while, foreach

4. Methods:
 
- Declaration and definition
- Method overloading
- Static methods
 
5. Object-Oriented Programming:
 
- Classes and objects
- Inheritance
- Polymorphism
- Encapsulation
- Interfaces

6. Collections:
 
- Arrays, Lists, Dictionaries
- LINQ (Language Integrated Query)

7. File I/O:
 
- Reading and writing files using  System.IO

8. Exception Handling:
 
- Try-catch blocks
- Custom exceptions
 
Example Code

```Csharp
using System;
using System.Collections.Generic;

class Program {
    static void Main() {
        List<int> numbers = new List<int> { 1, 2, 3, 4, 5 };
        numbers.Sort();
        foreach (int num in numbers) {
            Console.Write(num + " ");
        }
    }
}
```
Additional Resources
 
- Books:
 
- "The C++ Programming Language" by Bjarne Stroustrup
- "C# 8.0 and .NET Core 3.0" by Mark J. Price
- Online Tutorials:
 
- C++ Tutorial
- C# Tutorial
- Practice Sites:
 
- LeetCode
- HackerRank



































