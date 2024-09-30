# _APC_ - "_Algoritmos e Programação de Computadores_" 💻

_APC_ is a first semester subject of the _Computer Science_ course at _UnB_. It's taught by many professors, each one with its own way of teaching, I ended up with _Carla Castanho_ and _Franklin Ned_. The subject is divided into two parts: the first part is about algorithms and how to come with the code idea from scratch and the second part is about actually programming in _C language_. The subject is very important because it's the first contact with programming for many students and it's the base for many other subjects in the course. At the end of the semester you'll learn concepts like: variables, condictions, loops, functions, arrays, strings, pointers, structs, recursivity, etc. This is an introduction to coding, it wasn't meant to be hard. Good luck!

_obs._ This repo is based on my experience, it can be different for you.

## Topics 📋

- [Exercises 📝](#ancora1)
- [Project 👨‍💻](#ancora2)
- [Examns 🧠](#ancora3)
- [Content 📚](#ancora4)
  - [Algorithms 🧮](#ancora5)
    - [Representation of Algorithms 📊](#ancora6)
    - [Computational Algorithms 🤖](#ancora7)
  - [Programming in C 🖥️](#ancora8)
    - [Basic Structure 📜](#ancora9)
    - [Conditional Structures 🤓](#ancora10)
    - [Loops 🔄](#ancora11)
    - [Pointers 🧐](#ancora12)
    - [Functions 🛠️](#ancora13)
    - [Arrays 📁](#ancora14)
    - [Multidimensional Arrays 🗃️](#ancora15)
    - [Sorting algorithms 1️⃣,2️⃣,3️⃣, ...](#ancora16)
    - [Strings 🧵](#ancora17)
    - [Structs 🏗️](#ancora18)
    - [File Handling 📃](#ancora19)
- [Professors Feedback 👨‍🏫](#ancora20)
- [Contributing 🤝](#ancora21)
- [Extras 🎁](#ancora22)

<a name="ancora1"></a>

## Exercises 📝

The exercises is basic a list of problems in a online judge, [_Beecrowd_](https://judge.beecrowd.com), where you'll have to solve them using _C language_ (_it can change to python or Java, depending on your teacher_). The problems are divided into categories, like: _Beginner_, _Ad-Hoc_, _Strings_, _Data Structures_, etc. The exercises are very important because they'll help you to understand the concepts and to get used to coding. Our lists were made by _Vinícius Ruela_. **_Do as many exercises as you can_**, it's the best way to learn how to code and the exam is based on them, 3 of beecrowd problems.

_obs._ _These repos may help!_ &ensp; -> &ensp; [_Beecrowd-Solutions_](https://github.com/danhollenbach/Beecrowd-Solutions) &ensp; / &ensp; [_URI_](https://github.com/malbolgee/URI)

-> _Extra tip!_

- > In _Beecrowd_, go to preferences and turn on the _"Show problem subject"_ configuration (_it helps a lot_!).

<a name="ancora2"></a>

## Project 👨‍💻

The project is individual and different for each semester. Mine was a console game based on NumberSums, a grid game where you must erase numbers to reach a column or a line sum. It is very important cause it's the best way to really learn how to code. You'll have to use all the concepts you've learned in the semester to make it work.

_obs._ *You can check my project [*here*](https://github.com/danhollenbach/APC_Project_2024.1-AddNums), it's commented in english, really easy to understand what's going on.*

<a name="ancora3"></a>

## Exams 🧠

As mentined before the exams are based on the exercises, it can be a simple problem or a more complex one. But if you already done it you can copy and paste your code (_I don't know if it'll be this way anymore_). My semester was a true mess and I had some exams canceled. I wish you guys a different semester.

_obs._ _My past exams can be seen [here](https://github.com/LucasMABF/UnB/tree/main/2024.1/APC/provas)._

<a name="ancora4"></a>

# Content 📚

This tab is intended to summarize the content, it's very important to know what you're going to learn.

<a name="ancora5"></a>

## Algorithms 🧮

The representation of algorithms is essential for solving computational problems, and there are various ways to illustrate them, each with its advantages and disadvantages.

- **_Logic:_** Involves reasoning and organizing thought processes, crucial for understanding and modeling solutions to computational issues.
- **_Algorithm:_** A defined, finite sequence of steps to complete a task or solve a problem, emphasizing the importance of step order.
- **_Data vs. Information:_** Data are raw symbols representing facts, while information is meaningful data arranged in context.
- **_Input and Output:_** Problem-solving involves processing input data to generate expected output, acknowledging the importance of understanding both.
- **_Programming Logic:_** Focuses on creating sequences of instructions to solve problems based on given inputs, leading to desired outputs.

#### _Ex._

- > _Changing a Tire:_ Steps outlined to generalize the solution for any car.

<a name="ancora6"></a>

### Representation of Algorithms 📊

There are various forms of _Representation of Algorithms_ without a clear consensus on the best one. Each offers unique advantages and drawbacks:

- **_Narrative Description:_** Expresses algorithms in natural language, which can introduce ambiguities.
- **_Flowchart:_** Visual representation of steps but less emphasis in this context.
- **_Pseudocode:_** Simplified code-like representation, focusing on logic more than implementation specifics.

<a name="ancora7"></a>

### Computational Algorithms 🤖

Steps and structures necessary to solve problems using programming languages and data manipulation.

- **_Data Types:_**
  Data must conform to formats and restrictions, categorizing them into three primary types: - _Numeric:_ Contains integers or real numbers. - _Literal:_ Comprises sequences of characters also referred to as strings. - _Logical:_ Represents boolean values, either true or false.

- **_Concepts:_**

  - _Constants:_ Values that do not change throughout the program's execution. They must have a defined name, type, and value.
  - _Variables:_ Memory regions reserved for data storage, which can change during execution. Each variable needs a declared type and a unique name.
  - _Reserved Words:_ Special identifiers in a programming language that cannot be used for naming variables or constants.

- **_Rules:_**

  - _Variable Naming:_ Variables must start with a letter and must not contain reserved words.
  - _Variable Declaration:_ Typically occurs at the program's start, requires specifying a type and a name.

- **_Expressions and Operators:_**
  - _Arithmetic Operators:_ Used for mathematical calculations involving variables and constants.
  - _Logical Expressions:_ Used to assess conditions and return boolean values.
  - _Logical Operators:_ Include _AND_, _OR_, and _NOT_ that return boolean results.

<a name="ancora8"></a>

## Programming in C 🖥️

The _C programming language_, created in 1972, is a versatile, high-performance language widely used for system software development, including operating systems and compilers. It gained popularity for its efficiency and adaptability, particularly in the Unix operating system. The language is portable and provides high execution speed, making it suitable for a variety of projects. The course focuses on the ANSI standard of C, covering basic to advanced elements throughout the semester.

<a name="ancora9"></a>

### Basic Structure 📜

- **_Code comments:_** &ensp; `/* comment */`
- **_Operators:_**

  - _Arithmetic Operators:_ &ensp; _addition_ `+`, &ensp; _subtraction_ `-`, &ensp; _multiplication_ `*`, &ensp; _division_ `/`, &ensp; _modulus_ `%`.
  - _Logical Operators:_ &ensp; _and_ `&&`, &ensp; _or_ `||` , &ensp; _not_ `!` .
  - _Assignment Operators:_ &ensp; _addition_ `+=`, &ensp; _subtraction_ `-=`, &ensp; _multiplication_ `*=`, &ensp; _division_ `/=`, &ensp; _modulus_ `%=`.
  - _Relational Operators:_ &ensp; _equal to_ `==`, &ensp; _not equal to_ `!=`, &ensp; _greater than_ `>`, &ensp; _less than_ `<`, &ensp; _greater than or equal to_ `>=`, &ensp; _less than or equal to_ `<=` .

- **_Variable Types:_**
  Variables in C require a defined type, affecting memory allocation and data interpretation. Some common types include:

  - `int` -> Integer values.
  - `float` -> Floating-point values.
  - `char` -> Single character values.
  - `double` -> Double-precision floating-point values.

    _obs._ *For a more complete overview about *C* types click [here](https://en.wikipedia.org/wiki/C_data_types).*

- **_Declaring..._**

  - **_...Variables:_** `<data_type> <var_name> = <value>;` &nbsp; or &nbsp; `<data_type> <var_name>;` &nbsp;
    **_Ex._** `int valor = 2;`
    &nbsp;
  - **_...Constants:_** `#define <constant_name> <value>` &nbsp; or &nbsp; `const <data_type> <var_name> = <value>;` &nbsp;
    **_Ex._** `#define PI 3.14159`

- **_Macros:_**
  Macros are defined using the `#define` directive, which allows for creating constants without memory allocation. It is a preprocessor directive that replaces the macro name with its value throughout the code.
  `#define <macro_name> <value>`

- **_Input/Output Functions:_**
  The commands `printf` and `scanf` are used for outputting data to the screen and reading user input, respectively. There are other functions like `getchar()`, `putchar()`, `gets()`, `puts()`, `fgets()`, `fputs()`, `fscanf()`, `fprintf()`, but they are more harder to understand than the default _C_ input and output functions.

_obs._ The format specifier `%d` is used for integers, `%f` for floating-point numbers, `%c` for characters, and `%lf` for double. For more information about format specifiers click [here](https://www.tutorialspoint.com/cprogramming/c_input_output.htm).

- **_Sequential Structure:_**
  C executes commands line by line sequentially beginning at the main function, which is mandatory in all programs.

- **_Global vs Local Variables:_**
  _Global variables_ exist throughout the program, while _local variables_ only exist within their defined scope. - _Caution against overusing global variables; they complicate debugging and reduce the modularity of code._ - _Scope Precedence: Local variables take precedence over global ones even if they share the same name._

  ```c 
    #include <stdio.h>
    int x = 10; // global variable

    int main() {
        int x = 20; // local variable
        printf("%d", x); // prints 20
        return 0;
    }
  ```

<a name="ancora10"></a>

### Conditional Structures 🤓

Understanding conditional structures is essential for enabling decision-making capabilities within code. These structures allow for the execution of specific code blocks based on certain conditions, enhancing the program's flexibility and functionality. The _C language_ provides several conditional structures, each serving distinct purposes.

#### If Statement:

The if statement is a fundamental conditional structure that executes a block of code if a specified condition is true. If the condition is false, the block is skipped. (_Only a true condition executes the block!_)

The general syntax is as follows:

```c
if (condition) {
    // code block
}
```

##### _Ex._

```c
int age = 20;
if (age >= 18) {
    printf("You are an adult.");
}
```

#### If-Else Statement:

The if-else statement extends the functionality of the if statement by providing an alternative block of code to execute if the initial condition is false. This structure ensures that one of two actions is taken based on the condition's outcome.

```c
if (condition) {
    // code block 1
} else {
    // code block 2
}
```

##### _Ex._

```c
int grade = 85;
if (grade >= 60) {
    printf("You passed the exam.");
} else {
    printf("You failed the exam.");
}
```

#### Chained Conditional Structures:

Chained conditional structures allow for checking multiple conditions sequentially using else if. Only the first true condition's block is executed, providing a more complex decision-making process.

```c
if (condition1) {
    // code block 1
} else if (condition2) {
    // code block 2
} else {
    // code block 3
}
```

##### _Ex._

```c
int score = 75;
if (score >= 90) {
    printf("You received an A.");
} else if (score >= 80) {
    printf("You received a B.");
} else if (score >= 70) {
    printf("You received a C.");
} else {
    printf("You did not pass.");
}
```

#### Compound Conditions:

Compound conditions involve combining multiple conditions using logical operators: AND (&&), OR (||), and NOT (!). Each condition must be enclosed in parentheses to ensure proper evaluation.

```c
if ((condition1) && (condition2)) {
    // code block
}
```

##### _Ex._

```c
int num1 = 5, num2 = 10;
if ((num1 > 0) && (num2 < 20)) {
    printf("Both conditions are true.");
}
```

#### Switch Case Statement:

The switch case statement provides an alternative to if-else structures for managing multiple possible conditions based on discrete values. It is particularly useful for menu selection or other scenarios with predefined options. It is essential to include a break statement to prevent fall-through between cases.

```c
switch (expression) {
    case value1:
        // code block 1
        break;
    case value2:
        // code block 2
        break;
    default:
        // default code block
}
```

##### _Ex._

```c
int day = 3;
switch (day) {
    case 1:
        printf("Monday");
        break;
    case 2:
        printf("Tuesday");
        break;
    case 3:
        printf("Wednesday");
        break;
    default:
        printf("Invalid day");
}
```

<a name="ancora11"></a>

### Loops 🔄

Repetitive tasks are common in programming, and loops provide an efficient way to execute code multiple times based on specified conditions. The _C language_ offers three primary loop structures: for, while, and do-while loops.
_obs. One loop cycle is referred to as an iteration._

#### For Loop:

The for loop is a counted repetition structure that executes a block of code a specified number of times. It consists of three main components: initialization, condition, and increment/decrement. The loop continues until the condition is false. (_Counted repetition structure! Used when the number of iterations is known beforehand._)

> **_Key components_**
>
> - _Initialization_ (starting value)
> - _Condition_ (when to stop)
> - Increment/Decrement (how the index changes with each iteration)

```c
for (initialization; condition; increment/decrement) {
    // code block
}
```

##### _Ex._

```c
for (int i = 1; i <= 10; i++) {
    printf("%d ", i);
}
```

#### While Loop:

The while loop is a conditional repetition structure that executes a block of code as long as a specified condition remains true. The condition is evaluated before each iteration, and the loop stops when the condition becomes false. (_Conditional repetition with a test at the beginning!_)

```c
while (condition) {
    // code block
}
```

##### _Ex._

```c
int count = 1;
while (count <= 10) {
    printf("%d ", count);
    count++;
}
```

#### Do-While Loop:

The do-while loop is similar to the while loop but guarantees that the code block is executed at least once before evaluating the condition. The loop continues as long as the condition remains true. (_Conditional repetition with a test at the end!_)

```c
do {
    // code block
} while (condition);
```

##### _Ex._

```c
int num = 1;
do {
    printf("%d ", num);
    num++;
} while (num <= 10);
```

#### Nested Loops:

Nested loops involve placing one loop within another, allowing for more complex iterations. Each inner loop completes its full cycle for every iteration of the outer loop. (_It's important to use different variables for indices in nested loops to avoid confusion and errors._)

```c
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 3; j++) {
        // code block
    }
}
```

##### _Ex._

```c
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 3; j++) {
        printf("%d ", i * j);
    }
    printf("\n");
}
```

_obs._ _The output of the nested loop example will display the multiplication table up to 3x3 in a matrix!_

#### Efficiency Considerations:

While there is no theoretical limit to the number of nested loops, using more than three is rarely necessary or efficient. Excessive nesting can lead to code complexity and reduced readability, making it challenging to maintain and debug.

<a name="ancora12"></a>

### Pointers 🧐

Pointers are essential in _C programming_ for memory management and efficient data manipulation. They store memory addresses, allowing for direct access to variables and functions. Understanding pointers is crucial for mastering the language and optimizing code performance.

#### What is a Pointer?

In C, a pointer is a variable that stores the memory address of another variable. Instead of holding the actual value, a pointer holds the location of where the value is stored in memory.

#### Declaring:

A pointer is declared using an asterisk (\*) before the pointer's name.

```c
int *ptr;  // Declares a pointer to an integer
```

#### Manipulating:

To store the address of a variable, use the address-of operator (&).
To dereference a pointer and access the value at the memory address, use the dereference operator (\*).

```c
int num = 10;
ptr = &num;  // Assigns the address of `num` to `ptr`
printf("%d", *ptr);  // Prints the value stored in `num` (10)
```

_Ex._

```c
#include <stdio.h>

int main() {
    int num = 10;
    int *ptr = &num;  // Pointer storing the address of num

    printf("Value of num: %d\n", num);         // 10
    printf("Address of num: %p\n", ptr);       // Memory address of num
    printf("Value at ptr: %d\n", *ptr);        // 10 (dereferencing ptr)

    return 0;
}
```

<a name="ancora13"></a>

### Functions 🛠️

_Have you ever had a task that you need to perform multiple times in your code?_

In order to not repeat the same code multiple times, you can create a _function_ for it. _Functions_, or _subagotithms_, are self-contained blocks of code that perform specific tasks, they are essential for structuring and maintaining code effectively, allowing modular design, code reuse, a better debugging and code organization.

#### Structure:

- _Return Type:_ Indicates the type of value returned by the function. (_It can be any value type_)
- _Parameters:_ Variables passed to functions, which are essential for its operation and defined in the header.
  &nbsp;

  - _...by value:_ default way to pass function arguments by copying the variable's value. _(Changing the parameter within the function does not affect the original variable outside the function.)_
    &nbsp;
  - _...by reference:_ pass the adress in memory to the actual variable.(_Changes made to parameters in the function affect the original variables outside of the function._)

  _Ex._

  ```c
  void increment_copy(int x)   x++; // if the declarition is one line long,
  void increment_ref(int* x) (*x)++; // you can use it without curly braces.
  int main() {
      int num = 5;
      increment_copy(num);
      printf("%d", num); // prints 5
      increment_ref(&num);
      printf("%d", num); // prints 6
      return 0;
  }
  ```

  _obs._ _Functions can have no return, a `void` function, or return only one value by default._

##### Header:

Contains the return type, function name, and parameters.

```c
int add(int a, int b){} // function header
```

_obs._
-> _Function prototype:_ declarations that provide the function's signature that inform the compiler about the function's existence before its actual implementation, allowing for proper function calls. It's important to declare the function before the main function if you're going to use it in the main function.
_(Actually this is only to make the first function declared be the main, just a visual difference. If you don't mind you can declare all other function complete and place the main in the bottom of the code)._ `¯\_(ツ)_/¯`

```c
int add(int a, int b); // function prototype
```

##### Body:

Contains the implementation details and logic of the function.

```c
int add(int a, int b) {
    return a + b;
}
```

##### Scope:

Defined by curly braces {}, signifying the boundaries of the function.

```c
{
    // code block
}
```

#### Function Calls:

Functions are called by their name, and arguments are passed within parentheses. The return value can be stored in a variable or used directly in the code.

```c
add(5, 3); // function call
or
int sum = add(5, 3); // function call
or
printf("%d", add(5, 3)); // function call
```

#### Recursion:

Recursion is a powerful technique where a function calls itself to solve smaller instances of a problem. It is essential to have a base case to prevent infinite recursion.

```c
int factorial(int n) {
    if (n == 0) return 1;
    else return n * factorial(n - 1);
}
```

_obs._ _Recursion can be less efficient than iterative solutions due to the overhead of function calls and stack memory usage._

#### Multiple Returns:

Functions can simulate multiple returns by using pointers to modify variables passed as arguments. This technique allows for more than one value to be returned from a function.

```c
void multipleReturns(int a, int b, int* sum, int* product) {
    *sum = a + b;
    *product = a * b;
}
```

<a name="ancora14"></a>

### Arrays 📁

_Arrays_, also known as _vectors_, are essential data structures that allow for the storage and manipulation of multiple same type values using a single variable. They are particularly useful for managing large datasets efficiently.

#### Structure:

- _Type:_ Indicates the data type of the elements stored in the array.
- _Name:_ Unique identifier for the array.
- _Size:_ Number of elements the array can hold, _defined during declaration_.

```c
int numbers[5]; // array declaration
```

_obs._

- _Arrays are indexed from 0 to n-1, accessing out-of-bounds indices can lead to segmentation faults._
- _Arrays can be initialized during declaration or later using loops or direct assignment._
- _Arrays can be passed as parameters to functions, affecting the original array if modified within the function._
  - Two different approaches to pass arrays as parameters: specifying size, easist way, or not specifying size.

##### _Ex._

```c
void printArray(int arr[], int size) {
    for (int i = 0; i < size; i++) {
        printf("%d ", arr[i]);
    }
}
```

<a name="ancora15"></a>

### Multidimensional Arrays 🗃️

The efficient use of multidimensional arrays, particularly matrices, can significantly optimize memory management and data organization when handling large datasets.

#### Matrices:

Two-dimensional arrays essential for organizing data in rows and columns. They are commonly used in various applications, including image processing and mathematical computations.

- _Function Parameters with Matrices:_

  - _Using array notation:_

    - The function header should include the matrix type.
    - The sizes for dimensions beyond the first must be specified to ensure accurate memory access.

    _obs._ _This applies to arrays with more than one dimension too._

  ```c
  void printMatrix(int matrix[][3], int rows) {
      for (int i = 0; i < rows; i++) {
          for (int j = 0; j < 3; j++) {
              printf("%d ", matrix[i][j]);
          }
          printf("\n");
      }
  }
  ```

  - Using a pointer.
    - The function header should include a pointer to the matrix and the sizes of the dimensions.
    - The matrix is accessed using pointer arithmetic to navigate through memory locations.

  ```c
      void printMatrix(int *matrix, int rows, int cols) {
          for (int i = 0; i < rows; i++) {
              for (int j = 0; j < cols; j++) {
                  printf("%d ", *(matrix + i * cols + j));
              }
              printf("\n");
          }
      }
  ```

#### Memory Management:

Arrays are stored in contiguous memory locations, in a linear way, with elements aligned based on their data types. They represent a multidimensional matrix but are stored as a one dimensional array. Understanding the memory layout is crucial for accurate address calculations when accessing matrix elements.

_obs._ _To learn more about the topic click [here](https://www.ime.usp.br/~pf/algorithms/chapters/dynamic-allocation.html)._

<a name="ancora16"></a>

### Sorting algorithms 1️⃣,2️⃣,3️⃣, ...

Efficient search and sorting algorithms, like binary search and optimized bubble sort, are crucial for handling data structures effectively.

#### Searching:

Searching is a key method for retrieving information from various data structures, such as arrays and strings.

Two main searching methods discussed are linear search and binary search.

- _Linear Search:_ A straightforward method where each element is checked one by one until the target is found or the end of the data structure is reached.
  - Runs with a time complexity of O(n), making it less efficient for large datasets.
  ```c
  int linearSearch(int arr[], int size, int target) {
      for (int i = 0; i < size; i++) {
          if (arr[i] == target) return i;
      }
      return -1;
  }
  ```
- _Binary Search:_ A more efficient method that requires a sorted data set and follows the "divide and conquer" strategy.
  - It repeatedly divides the search interval in half, significantly reducing the number of comparisons.
  - Complexity of binary search is O(log n), which is more efficient than linear search's O(n).
  ```c
  int binarySearch(int arr[], int size, int target) {
      int left = 0, right = size - 1;
      while (left <= right) {
          int mid = left + (right - left) / 2;
          if (arr[mid] == target) return mid;
          else if (arr[mid] < target) left = mid + 1;
          else right = mid - 1;
      }
      return -1;
  }
  ```

#### Sorting:

Sorting involves arranging elements based on some criteria. Several algorithms exist for sorting, including [BubbleSort](https://www.geeksforgeeks.org/c-bubble-sort/), [QuickSort](https://www.geeksforgeeks.org/quick-sort-in-c/), and [HeapSort](https://www.geeksforgeeks.org/heap-sort/).

##### BubbleSort:

A simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order (_It's not the best sorting algorithm but this is all you need in the first semester_).

- Runs with a time complexity of O(n²) in the worst case, making it impractical for large datasets.
- Optimizations can be implemented to improve performance in certain scenarios, transforming the complexity to O(n) in the best case.

```c
void bubbleSort(int arr[], int size) {
    for (int i = 0; i < size - 1; i++) {
        for (int j = 0; j < size - i - 1; j++) {
            if (arr[j] > arr[j + 1]) {
                int temp = arr[j];
                arr[j] = arr[j + 1];
                arr[j + 1] = temp;
            }
        }
    }
}
```

##### Improving BubbleSort:

An optimized bubble sort can stop early if no swaps are made during a pass, increasing its efficiency.

```c
void optimizedBubbleSort(int arr[], int size) {
    for (int i = 0; i < size - 1; i++) {
        int swapped = 0;
        for (int j = 0; j < size - i - 1; j++) {
            if (arr[j] > arr[j + 1]) {
                int temp = arr[j];
                arr[j] = arr[j + 1];
                arr[j + 1] = temp;
                swapped = 1;
            }
        }
        if (swapped == 0) break;
    }
}
```

##### Algorithm Analysis:

The analysis of algorithms determines their correctness and performance in terms of time and space complexity.
[Big-O notation](https://en.wikipedia.org/wiki/Big_O_notation) is essential for understanding the efficiency of algorithms and comparing their performance.

<a name="ancora17"></a>

### Strings 🧵

Strings are sequences of characters stored in memory as a array, with each character represented by a numerical code. The `<string.h>` library provides various functions for string operations, simplifying common tasks like concatenation (`strcat`), comparison (`strcmp`), and length measurement (`strlen`). Understanding how they are represented in _C_ is crucial for effective manipulation and utilization of textual data within software applications. By mastering their manipulation techniques, programmers can develop robust applications that handle textual data efficiently.

#### _Ex._

```c
#include <stdio.h>
#include <string.h>
int main() {
    char str_input[20];
    char str1[20] = "Hello";
    char str2[20] = " World";

    gets(str_input); // Read input and store in string_input
    printf("String 1: %s\n", str1); // String 1: "Hello"
    printf("String 2: %s\n", str2); // String 2: " World"
    strcat(str1, str2); // Gather strings 1 and 2 and store in string 1
    printf("Concatenated String: %s\n", str1); // print "Hello World"
    printf("Length of String 1: %d\n", strlen(str1));   // Length of String 1: 12
    strcpy(str2, "Goodbye");    // Copy "Goodbye" to string 2
    printf("Copied String: %s\n", str2); // Copied String: "Goodbye". Was " World"
    return 0;
}
```

- _Character Representation:_ Computers operate mainly on numbers and utilize numerical codes to represent characters.
- _Code Systems:_ Various coding standards exist, such as _EBCDIC_, _ASCII_, _UTF-8_, and _UTF-16_, with _[ASCII](https://en.wikipedia.org/wiki/ASCII)_ being commonly used in _ANSI C_ where each character takes up 1 byte.

_obs._ _There are multiples ways to read a string and `gets()` is a great option._

- _String Declaration:_ Strings are declared as character arrays, with the last element reserved for the null character ('\0').
- _String Initialization:_ Strings can be initialized during declaration or later using assignment.
- _String Concatenation:_ The `strcat()` function is used to concatenate strings, appending the second string to the first.
- _String Comparison:_ The `strcmp()` function compares two strings lexicographically, returning 0 if they are equal.
- _String Length:_ The `strlen()` function calculates the length of a string, excluding the null character.
- _String Copy:_ The `strcpy()` function copies the contents of one string to another.

<a name="ancora18"></a>

### Structs 🏗️

Structs enable the grouping of related data of different types into a single composite data type, facilitating structured programming and data management. They are particularly useful for organizing complex data structures like employee records, game characters, and more.

#### _Ex._

```c
#include <stdio.h>
#include <string.h>

struct Monster {
    char name[20];
    int level;
    int stats[3];
};

int main() {
    struct Monster monster1;
    struct Monster monster2;
    printf("Enter monster 1 name: ");
    gets(monster1.name);
    printf("Enter monster 1 level: ");
    scanf("%d", &monster1.level);
    printf("Enter monster 1 stats: ");
    for (int i = 0; i < 3; i++) {
        scanf("%d", &monster1.stats[i]);
    }
    printf("Enter monster 2 name: ");
    gets(monster2.name);
    printf("Enter monster 2 level: ");
    scanf("%d", &monster2.level);
    printf("Enter monster 2 stats: ");
    for (int i = 0; i < 3; i++) {
        scanf("%d", &monster2.stats[i]);
    }
    printf("Monster 1: %s, Level: %d, Stats: %d %d %d\n", monster1.name, monster1.level, monster1.stats[0], monster1.stats[1], monster1.stats[2]);
    printf("Monster 2: %s, Level: %d, Stats: %d %d %d\n", monster2.name, monster2.level, monster2.stats[0], monster2.stats[1], monster2.stats[2]);
    return 0;
}
```

- _Struct Declaration:_ A new data type is defined using struct, which can include various fields with different data types.
- _Accessing Struct Fields:_ Individual fields within a struct can be accessed using the dot operator (.) for instances.
- _Pointers to Structs:_ Structs can be manipulated using pointers, allowing for functions to alter the contained data.
  - Access can be done either by dereferencing pointers or using the arrow operator (->).
- _Typedef for Structs:_ Typedef simplifies struct declarations by creating an alias for the struct type.
- _Array of Structs:_ Arrays can store multiple instances of structs, enabling the management of multiple records.
- _Sorting Structs:_ Structs can be sorted based on specific fields using sorting algorithms, enhancing data organization.
- _Memory Layout of Structs:_ Structs are stored in contiguous memory locations, similar to arrays, with attributes aligned according to their data types.

<a name="ancora19"></a>

### File Handling 📃

Files are organized data entities within non-volatile memory, managed by the operating system as streams of bytes. Understanding file manipulation in _C_ is essential for managing data persistence beyond program execution, particularly with text files.

- _File Operations in C:_ Files are managed using pointers (FILE\* fd) and opened using the `fopen()` function with specified access modes.
- _Writing Data:_ Data can be written back to text files using the `fprintf()` function.
- _Reading Data:_ Data can be read from text files using functions like `fscanf()`, `fgetchar()`, and `fgets()`.
- _Positioning in Files:_ The current file position can be managed using functions like `rewind()`, `ftell()`, and `fseek()`.
- _File Closing:_ Proper file closure is essential for freeing resources and saving changes using the `fclose()` function.
- _Common File Opening Errors:_ Issues like file non-existence or permission restrictions can prevent successful file access.
- _Importance of Proper Closure:_ Ensures all operations in the buffer are written to the file, preventing data loss upon program termination.
- _Error Handling:_ Checking file status after operations is crucial for detecting errors and ensuring proper file handling.

- **_Text files:_** store data as characters.
  - Opening Modes:
    - Read ("r")
    - Write ("w")
    - Append ("a")
    - Read/Write ("r+")
    - Create/Write ("w+")
    - Append/Read ("a+").
- **_Binary Files:_** Store data in binary format, allowing for efficient storage and retrieval of complex data structures.
  - _Advantages of Binary Files:_
    - Preserve data exactly as in memory.
    - Support complex data structures like arrays and structs.
  - _Binary File Visualization:_ Tools like WinHex (Windows) or Linux commands (hexdump, xxd) help visualize binary file content in hexadecimal form.
  - _Opening Binary Files:_ Similar to text files but with a 'b' in the mode when using `fopen()`.
  - _Reading and Writing:_ `fread()` and `fwrite()` functions are used for binary file operations, taking parameters like buffer pointer, size, count, and file stream.
  - _Error Handling and State Checking:_ After operations, file status should be checked for errors using `feof()` and `ferror()` functions.
  - _Practical Examples:_ Simple examples demonstrate reading from and writing to binary files containing student records using predefined structs.

#### _Ex._

```c
#include <stdio.h>

int main() {
    FILE *file;
    char filename[20];
    char text[100];

    printf("Enter the file name: ");
    gets(filename);

    file = fopen
    (filename, "w");
    if (file == NULL) {
        printf("Error opening file.\n");
        return 1;
    }

    printf("Enter text to write to the file: ");
    gets(text);

    fprintf(file, "%s", text);
    fclose(file);

    file = fopen(filename, "r");
    if (file == NULL) {
        printf("Error opening file.\n");
        return 1;
    }

    printf("Contents of the file:\n");
    while (fgets(text, 100, file) != NULL) {
        printf("%s", text);
    }

    fclose(file);
    return 0;
}
```

<a name="ancora20"></a>

## Professors Feedback 👨‍🏫

Being real, the lack of professionalism of both teachers is something apart. _Carla Castanho_ doesn't know how to teach, I guess the last time she coded in _C_ was 20 years ago (not even joking), the peak of her class is a slide reading (if she goes to the class). _Franklin Ned_ is a little better, but he's not good either. He knows how to teach, but doesn't seem like he wants. May leave the class earlier to go have some _pastel_ and sugarcane juice. In the other hand, others students say that _Vinícius Ruela_ and _Ishikawa_ are good teachers.

<a name="ancora21"></a>

## Contributing 🤝

_Do you feel that something is missing?_
Open an issue or a pull request and help me make a better repo for our new freshmen!

<a name="ancora22"></a>

## Extras 🎁

- [link](https://carlacastanho.github.io/Material-de-APC/) to Carla's site (_The monitors did it_).
- [link](https://www.onlinegdb.com/online_c_compiler) to a online _C_ compiler.
- [link](https://www.youtube.com/playlist?list=PL8iN9FQ7_jt4DJbeQqv--jpTy-2gTA3Cp) to a complete playlist of _C language_ on youtube. (_it's in portuguese_)
- [link](https://stackoverflow.com/) to Stack _Overflow_, where you can find answers to your questions.
- [link](https://www.classcentral.com/report/cs50-free-certificate/) to an article about _CS50_ (_if you are completely raw to coding I recommend taking a look. It's free!_)
  - [link](https://cs50.harvard.edu/ap/2025/syllabus/) to the course.
  - [link](https://cs50.harvard.edu/ap/2025/curriculum/) to the course curriculum.
