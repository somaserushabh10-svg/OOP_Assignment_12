Type Casting and Casting Operators in C++

📌 Overview

This project demonstrates type casting and casting operators in C++. It explains implicit type conversion, explicit type conversion, and the use of the static_cast operator with simple examples.

🎯 Objectives

Understand type casting in C++.

Learn implicit and explicit type conversion.

Convert values between int and double.

Understand and implement the static_cast operator.

Observe how type conversion affects values.

🛠️ Technologies Used

Language: C++

Compiler: GCC / MinGW

IDE: Dev-C++ / Visual Studio Code

Header File: iostream

📚 Concepts Covered

1. Implicit Type Casting

Implicit casting is performed automatically by the compiler when converting one data type into another.

int a = 10;
double b = a;

2. Explicit Type Casting

Explicit casting is performed manually by the programmer.

double x = 25.75;
int y = (int)x;

The fractional part is discarded, so y becomes 25.

3. static_cast

static_cast is a C++ casting operator used for supported explicit conversions.

int num = 100;
double result = static_cast<double>(num);

💻 Program Features

Converts an integer to a double using implicit casting.

Converts a double to an integer using explicit casting.

Uses static_cast for explicit type conversion.

Displays the original and converted values.

▶️ How to Run

Clone or download this repository.

Open the project folder in your IDE.

Open the C++ source file.

Compile and run the program.

Alternatively, compile using GCC:

g++ type_casting.cpp -o type_casting

Run on Windows:

type_casting.exe

🖥️ Sample Output

Implicit Type Casting:
Integer value = 10
Double value = 10

Explicit Type Casting:
Double value = 25.75
Integer value = 25

Using static_cast:
Integer value = 100
Double value = 100

📂 Project Structure

Type-Casting-Assignment/
├── type_casting.cpp
└── README.md

📊 Result

The program successfully demonstrates implicit casting, explicit casting, and the static_cast operator. It shows how values are converted between integer and double data types.

✅ Conclusion

This project helped me understand type casting and casting operators in C++. It demonstrates how implicit and explicit conversions work and how static_cast provides a clear way to perform supported conversions.
