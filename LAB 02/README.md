
# Programming Lab Task – C++

**Course:** CET  
**Semester:** 1st Semester  
**Language:** C++

## Objective

Write a C++ program that takes two integer numbers from the user and displays:

1. Remainder of both numbers
2. Average of both numbers
3. Square of the first number
4. Square of the second number

## C++ Source Code

```cpp
#include <iostream>
using namespace std;

int main()
{
    int num1, num2;

    // Input two integer numbers
    cout << "Enter first number: ";
    cin >> num1;

    cout << "Enter second number: ";
    cin >> num2;

    // Display remainder
    cout << "Remainder = " << num1 % num2 << endl;

    // Display average
    cout << "Average = " << (num1 + num2) / 2.0 << endl;

    // Square of first number
    cout << "Square of first number = " << num1 * num1 << endl;

    // Square of second number
    cout << "Square of second number = " << num2 * num2 << endl;

    return 0;
}
```

## Sample Input

```text
Enter first number: 10
Enter second number: 3
```

## Sample Output

```text
Remainder = 1
Average = 6.5
Square of first number = 100
Square of second number = 9
```

## Formulas Used

- Remainder = num1 % num2
- Average = (num1 + num2) / 2.0
- First Number Square = num1 * num1
- Second Number Square = num2 * num2

## How to Run in Dev-C++

1. Open Dev-C++.
2. Create a new source file.
3. Copy and paste the C++ code.
4. Save the file with .cpp extension.
5. Compile and run the program.
6. Enter two integer numbers.

## Important Note

The second number must not be zero because the remainder operator (%) cannot divide by zero.

## Rubric – Total 10 Marks

| Assessment Criteria | Marks |
|---|---:|
| Correct Program Structure | 2 |
| Correct Input from User | 2 |
| Correct Formulas | 3 |
| Correct Output Display | 2 |
| Program Runs Without Error | 1 |
| **Total** | **10** |
