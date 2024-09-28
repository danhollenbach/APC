# *APC* - "*Algoritmos e Programação de Computadores*" 💻
*APC* is a first semester subject of the *Computer Science* course at *UnB*. It's taught by many professors, each one with its own way of teaching, I ended up with *Carla Castanho* and *Franklin Ned*. The subject is divided into two parts: the first part is about algorithms and how to come with the code idea from scratch and the second part is about actually programming in *C language*. The subject is very important because it's the first contact with programming for many students and it's the base for many other subjects in the course. At the end of the semester you'll learn concepts like: variables, condictions, loops, functions, arrays, strings, pointers, structs, recursivity, etc. This is an introduction to coding, it wasn't meant to be hard. Good luck!

*obs.* This repo is based on my experience, it can be different for you.

## Exercises 📝
The exercises is basic a list of problems in a online judge, [*Beecrowd*](https://judge.beecrowd.com), where you'll have to solve them using *C language* (*it can change to python or Java, depending on your teacher*). The problems are divided into categories, like: *Beginner*, *Ad-Hoc*, *Strings*, *Data Structures*, etc. The exercises are very important because they'll help you to understand the concepts and to get used to coding. Our lists were made by *Vinícius Ruela*. ***Do as many exercises as you can***, it's the best way to learn how to code and the exam is based on them, 3 of beecrowd problems.

*obs.* *These repos may help!* &ensp; -> &ensp; [*Beecrowd-Solutions*](https://github.com/danhollenbach/Beecrowd-Solutions) &ensp; / &ensp; [*URI*](https://github.com/malbolgee/URI)

-> *Extra tip!*
- >In *Beecrowd*, go to preferences and turn on the *"Show problem subject"* configuration (*it helps a lot*!).

## Project 👨‍💻
The project is individual and different for each semester. Mine was a console game based on NumberSums, a grid game where you must erase numbers to reach a column or a line sum. It is very important cause it's the best way to really learn how to code. You'll have to use all the concepts you've learned in the semester to make it work.

*obs.* *You can check my project [*here*](https://github.com/danhollenbach/APC_Project_2024.1-AddNums), it's commented in english, really easy to understand what's going on.*


## Exams 🧠
As mentined before the exams are based on the exercises, it can be a simple problem or a more complex one. But if you already done it you can copy and paste your code (*I don't know if it'll be this way anymore*). My semester was a true mess and I had some exams canceled. I wish you guys a different semester.

*obs.* *My past exams can be seen [here](https://github.com/LucasMABF/UnB/tree/main/2024.1/APC/provas).*

# Content 📚
This tab is intended to summarize the content, it's very important to know what you're going to learn.
## Algorithms 🧮
The representation of algorithms is essential for solving computational problems, and there are various ways to illustrate them, each with its advantages and disadvantages.

- ***Logic:*** Involves reasoning and organizing thought processes, crucial for understanding and modeling solutions to computational issues.
- ***Algorithm:*** A defined, finite sequence of steps to complete a task or solve a problem, emphasizing the importance of step order.
- ***Data vs. Information:*** Data are raw symbols representing facts, while information is meaningful data arranged in context.
- ***Input and Output:*** Problem-solving involves processing input data to generate expected output, acknowledging the importance of understanding both.
- ***Programming Logic:*** Focuses on creating sequences of instructions to solve problems based on given inputs, leading to desired outputs.
#### *Ex.*
- > *Changing a Tire:* Steps outlined to generalize the solution for any car.
### Representation of Algorithms 📊
There are various forms of *Representation of Algorithms* without a clear consensus on the best one. Each offers unique advantages and drawbacks:
- ***Narrative Description:*** Expresses algorithms in natural language, which can introduce ambiguities.
- ***Flowchart:*** Visual representation of steps but less emphasis in this context.
- ***Pseudocode:*** Simplified code-like representation, focusing on logic more than implementation specifics.

### Computational Algorithms 🤖
Steps and structures necessary to solve problems using programming languages and data manipulation.

- ***Data Types:*** 
Data must conform to formats and restrictions, categorizing them into three primary types:
    - *Numeric:* Contains integers or real numbers.
    - *Literal:* Comprises sequences of characters also referred to as strings.
    - *Logical:* Represents boolean values, either true or false.

- ***Concepts:***
    - *Constants:* Values that do not change throughout the program's execution. They must have a defined name, type, and value.
    - *Variables:* Memory regions reserved for data storage, which can change during execution. Each variable needs a declared type and a unique name.
    - *Reserved Words:* Special identifiers in a programming language that cannot be used for naming variables or constants.

- ***Rules:***
    - *Variable Naming:* Variables must start with a letter and must not contain reserved words.
    - *Variable Declaration:* Typically occurs at the program's start, requires specifying a type and a name.

- ***Expressions and Operators:***
    - *Arithmetic Operators:* Used for mathematical calculations involving variables and constants.
    - *Logical Expressions:* Used to assess conditions and return boolean values.
    - *Logical Operators:* Include *AND*, *OR*, and *NOT* that return boolean results.

## Programming in C 🖥️

The *C programming language*, created in 1972, is a versatile, high-performance language widely used for system software development, including operating systems and compilers. It gained popularity for its efficiency and adaptability, particularly in the Unix operating system. The language is portable and provides high execution speed, making it suitable for a variety of projects. The course focuses on the ANSI standard of C, covering basic to advanced elements throughout the semester.

### Basic Structure 📜
- ***Code comments:*** &ensp; ```/* comment */```
- ***Operators:***
    - *Arithmetic Operators:* &ensp; *addition* ```+```, &ensp; *subtraction* ```-```, &ensp; *multiplication* ```*```, &ensp; *division* ```/```, &ensp; *modulus* ```%```.
    - *Logical Operators:* &ensp; *and* ```&&```,  &ensp; *or* ```||``` , &ensp; *not* ```!``` .
    - *Assignment Operators:* &ensp; *addition* ```+=```, &ensp; *subtraction* ```-=```, &ensp; *multiplication* ```*=```, &ensp; *division* ```/=```, &ensp; *modulus* ```%=```.
    - *Relational Operators:* &ensp; *equal to* ```==```, &ensp; *not equal to* ```!=```, &ensp; *greater than* ```>```, &ensp; *less than* ```<```, &ensp; *greater than or equal to* ```>=```, &ensp; *less than or equal to* ```<=``` .

- ***Variable Types:***
Variables in C require a defined type, affecting memory allocation and data interpretation. Some common types include:

    - ```int``` -> Integer values.
    - ```float``` -> Floating-point values.
    - ```char``` -> Single character values.
    - ```double``` -> Double-precision floating-point values.

        *obs.* *For a more complete overview about *C* types click [here](https://en.wikipedia.org/wiki/C_data_types).* 

- ***Declaring...***

    - ***...Variables:*** ```<data_type> <var_name> = <value>;``` &nbsp; or &nbsp; ```<data_type> <var_name>;``` &nbsp; 
    ***Ex.*** ```int valor = 2;```
    &nbsp; 
    - ***...Constants:*** ```#define <constant_name> <value>``` &nbsp; or &nbsp; ```const <data_type> <var_name> = <value>;``` &nbsp; 
    ***Ex.*** ```#define PI 3.14159```



- ***Macros:***
Macros are defined using the ```#define``` directive, which allows for creating constants without memory allocation. It is a preprocessor directive that replaces the macro name with its value throughout the code.
```#define <macro_name> <value>```

- ***Input/Output Functions:*** 
The commands ```printf``` and ```scanf``` are used for outputting data to the screen and reading user input, respectively. There are other functions like ```getchar()```, ```putchar()```, ```gets()```, ```puts()```, ```fgets()```, ```fputs()```, ```fscanf()```, ```fprintf()```, but they are more harder to understand than the default *C* input and output functions.

*obs.* The format specifier ```%d``` is used for integers, ```%f``` for floating-point numbers, ```%c``` for characters, and ```%lf``` for double. For more information about format specifiers click [here](https://www.tutorialspoint.com/cprogramming/c_input_output.htm).
- ***Sequential Structure:***
C executes commands line by line sequentially beginning at the main function, which is mandatory in all programs. 

### Conditional Structures 🤓
Understanding conditional structures is essential for enabling decision-making capabilities within code. These structures allow for the execution of specific code blocks based on certain conditions, enhancing the program's flexibility and functionality. The *C language* provides several conditional structures, each serving distinct purposes. 

#### If Statement:
The if statement is a fundamental conditional structure that executes a block of code if a specified condition is true. If the condition is false, the block is skipped. (*Only a true condition executes the block!*)

The general syntax is as follows:
```c
if (condition) {
    // code block
}
```
##### *Ex.*
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
##### *Ex.*
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
##### *Ex.*
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
##### *Ex.*
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
##### *Ex.*
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
### Loops 🔄
Repetitive tasks are common in programming, and loops provide an efficient way to execute code multiple times based on specified conditions. The *C language* offers three primary loop structures: for, while, and do-while loops.
*obs. One loop cycle is referred to as an iteration.*

#### For Loop:
The for loop is a counted repetition structure that executes a block of code a specified number of times. It consists of three main components: initialization, condition, and increment/decrement. The loop continues until the condition is false. (*Counted repetition structure! Used when the number of iterations is known beforehand.*)
>***Key components***
> - *Initialization* (starting value)
> - *Condition* (when to stop)
> - Increment/Decrement (how the index changes with each iteration)
```c   
for (initialization; condition; increment/decrement) {
    // code block
}
```
##### *Ex.*
```c
for (int i = 1; i <= 10; i++) {
    printf("%d ", i);
}
```
#### While Loop:
The while loop is a conditional repetition structure that executes a block of code as long as a specified condition remains true. The condition is evaluated before each iteration, and the loop stops when the condition becomes false. (*Conditional repetition with a test at the beginning!*)
```c
while (condition) {
    // code block
}
```
##### *Ex.*
```c
int count = 1;
while (count <= 10) {
    printf("%d ", count);
    count++;
}
```
#### Do-While Loop:
The do-while loop is similar to the while loop but guarantees that the code block is executed at least once before evaluating the condition. The loop continues as long as the condition remains true. (*Conditional repetition with a test at the end!*)
```c
do {
    // code block
} while (condition);
```
##### *Ex.*
```c
int num = 1;
do {
    printf("%d ", num);
    num++;
} while (num <= 10);
```
#### Nested Loops:
Nested loops involve placing one loop within another, allowing for more complex iterations. Each inner loop completes its full cycle for every iteration of the outer loop. (*It's important to use different variables for indices in nested loops to avoid confusion and errors.*)
```c
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 3; j++) {
        // code block
    }
}
```
##### *Ex.*
```c
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 3; j++) {
        printf("%d ", i * j);
    }
    printf("\n");
}
```
*obs.* *The output of the nested loop example will display the multiplication table up to 3x3 in a matrix!*
#### Efficiency Considerations:
While there is no theoretical limit to the number of nested loops, using more than three is rarely necessary or efficient. Excessive nesting can lead to code complexity and reduced readability, making it challenging to maintain and debug.







Understanding the different types of loop structures in programming—specifically while and do-while loops—enables more effective control flow in coding.

Summary
Introduction to Loop Structures: The content discusses repetition structures in programming, focusing on conditional loops.
Laço while (While Loop):
Executes a block of code as long as a specified condition is true.
Begins with a condition check before executing the loop.
Example 1: Validates user input for gender until correct values ('M', 'm', 'F', 'f') are provided before reading the year.
Example 2: Calculates the factorial of a given number by multiplying from 1 to the number.
Laço do-while (Do-While Loop):
Executes a block of code first and then checks a condition afterward; guarantees at least one execution.
Example: Reads integers and sums them until the user enters 0. Even if 0 is entered first, the body executes once.
Recommended Exercises: List includes various problems (e.g., calculating averages, identifying odd/even numbers) to reinforce understanding of loop concepts.
Authors: Created by Thiago Veras and Giovanni M Guidini.
Related queries:

What are the differences between while and do-while loops?
How is user input validated in the provided examples?
What programming problems can help practice loop structures?


Key Takeaway
Subalgorithms, or functions, are essential for structuring and maintaining code effectively, allowing modular design, reducing redundancy, and facilitating debugging.

Summary
Definition of Subalgorithms: Subalgorithms are small, self-contained programs (functions) that can be reused multiple times within a larger program.
Benefits of Using Functions:
Improves code readability and maintainability.
Reduces code repetition, thereby minimizing potential errors.
Simplifies debugging and management of large codebases.
Structure of Functions:
Header: Contains the return type, function name, and parameters.
Body: Contains the implementation details and logic of the function.
Scope: Defined by curly braces {}, signifying the boundaries of the function.
Function Types: Functions can return values or be void (no return). Their type must match what is specified in the header.
Return Statement: Indicates results provided by the function; only one value can be returned, except for void functions.
Parameters: External variables passed to functions, which are essential for function operation and defined in the header.
Examples of Functions:
Functions can be void with no parameters.
Functions can be void with parameters to carry out specific operations.
Functions with a return value and parameters that compute results, such as finding prime numbers.
Recommended Exercises: Various coding challenges designed to practice the concepts learned.
Global vs Local Variables:
Global variables exist throughout the program, while local variables only exist within their defined scope.
Caution against overusing global variables; they complicate debugging and reduce the modularity of code.
Scope Precedence: Local variables take precedence over global ones even if they share the same name.
Challenges: Programming exercises to apply the knowledge of functions and scope.
Related queries:

What are the advantages of using subalgorithms in programming?
How does scope affect variable accessibility in functions?
Can a function in C return multiple values?

Key Takeaway
Understanding the difference between value and reference parameters in C functions is crucial for effective programming, as it impacts how data is manipulated within functions.

Summary
The webpage is an educational resource focusing on "Subalgoritmos II," covering advanced topics in the C programming language, particularly function parameters.
Introduces function parameters as external values used within functions, classified into two categories: value and reference.
Parameters by Value:
Default way to pass function arguments by copying the variable's value.
Changing the parameter within the function does not affect the original variable outside the function.
Example code illustrates how modifications within a function do not alter the original variable.
Parameters by Reference:
Instead of copying, these parameters provide a reference (or pointer) to the actual variable.
Changes made to parameters in the function affect the original variables outside of the function.
The webpage provides a code example that demonstrates how to increment a variable using a reference.
Discusses the aspect of multiple returns using pointers to simulate returning more than one value from a function.
Suggested exercises for practicing these concepts are available, including links to coding challenges.
Extra materials are provided to help understand multiple returns and their implications within functions.
Related queries:

What is the difference between parameters by value and parameters by reference in C?
How can multiple values be returned in a C function?
What are some recommended exercises for practicing C function parameters?

Key Takeaway
Vectors (arrays) are essential for efficiently managing large datasets in programming, allowing for the storage and manipulation of multiple values with a single variable.

Summary
Introduction to vectors as a solution for handling large datasets of the same type.
Vectors enable programs to manage sequences without needing multiple individual variables.
The structure of a vector includes its type, name, and size.
Vectors are indexed from 0 to n-1, allowing for constant time access to their elements.
Accessing out-of-bounds indices can lead to segmentation faults, which is a common error in programming.
Vectors can be passed as parameters to functions, affecting the original vector if modified within the function.
Two different approaches to pass vectors as parameters: specifying size or not specifying size.
Various example problems involving vectors, such as calculating scores in a competition between two classes of students.
Introduction to dynamic vectors and memory management using malloc and memset for flexibility.
Importance of freeing allocated memory to avoid memory leaks.
Related queries:

What is the purpose of vectors in programming?
How do you avoid segmentation faults when using arrays?
What are the differences between static and dynamic vectors?

Key Takeaway
Efficient search and sorting algorithms, like binary search and optimized bubble sort, are crucial for handling data structures effectively in programming.

Summary
Introduction to Searching:

Searching is a key programming method for retrieving information from various data structures, such as arrays and strings.
Two main searching methods discussed are linear search and binary search.
Linear Search:

A straightforward method where each element is checked one by one until the target is found or the end of the data structure is reached.
Example algorithm is provided in C.
Binary Search:

A more efficient method that requires a sorted data set and follows the "divide and conquer" strategy.
It repeatedly divides the search interval in half, significantly reducing the number of comparisons.
Complexity of binary search is O(log n), which is more efficient than linear search's O(n).
Sorting:

Sorting involves arranging elements based on some criteria. Several algorithms exist for sorting, including QuickSort, HeapSort, and BubbleSort.
BubbleSort:

A simple but inefficient sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
Runs with a time complexity of O(n²) in the worst case, making it impractical for large datasets.
Optimizations can be implemented to improve performance in certain scenarios, transforming the complexity to O(n) in the best case.
Improving BubbleSort:

An optimized bubble sort can stop early if no swaps are made during a pass, increasing its efficiency.
Algorithm Analysis:

The analysis of algorithms determines their correctness and performance in terms of time and space complexity.
Big-O notation is essential for understanding the efficiency of algorithms and comparing their performance.
Recommended Exercises and Extra Materials:

Lists exercises for practice and materials for further reading about algorithm analysis and complexity.
Related queries:

What are the differences between linear search and binary search?
How does the time complexity of BubbleSort compare with more efficient sorting algorithms?
What optimizations can be applied to improve the performance of sorting algorithms?

Key Takeaway
The efficient use of multidimensional arrays, particularly matrices, can significantly optimize memory management and data organization when handling large datasets in programming.

Summary
Introduction to Multidimensional Arrays:

Explains the concept of multidimensional arrays as a necessary evolution from one-dimensional arrays, highlighting scenarios where they are more efficient.
Introduces the need for managing multiple variables succinctly and the idea of 'vector of vectors' to store data for complex structures.
Definition of Matrices:

Defines matrices as two-dimensional arrays essential for organizing data in rows and columns.
Describes similarities between working with matrices and one-dimensional arrays in C programming.
Function Parameters with Matrices:

Discusses how matrices can be passed as parameters to functions using two approaches:
Using a pointer.
Using array notation, with an emphasis on explicitly declaring sizes for dimensions beyond the first.
Code Examples:

Provides example code demonstrating how to count even numbers in a matrix and display the matrix.
Offers a downloadable code sample for further exploration.
Memory Management:

Describes how multidimensional arrays are stored in contiguous memory locations.
Explains the necessity of knowing dimensions for accurate address calculations when accessing matrix elements.
Recommended Exercises:

Lists various programming problems related to matrix manipulation to practice skills and reinforce concepts learned.
Additional Resources:

Links to extra materials discussing the nuances of passing arrays to functions and other programming practices related to matrices.
Related queries:

What are the advantages of using matrices over one-dimensional arrays in programming?
How do you correctly pass a 2D array as a function parameter in C?
Can you explain memory allocation for multidimensional arrays in C?

Key Takeaway
Understanding how strings are represented in C programming is crucial for effective manipulation and utilization of textual data within software applications.

Summary
Character Representation: Computers operate mainly on numbers and utilize numerical codes to represent characters.
Code Systems: Various coding standards exist, such as EBCDIC, ASCII, UTF-8, and UTF-16, with ASCII being commonly used in ANSI C where each character takes up 1 byte.
Strings as Character Sequences: A string is defined as a sequence of characters stored in an array, with the end denoted by a null character ('\0').
String Operations: Multiple operations can be performed with strings in C including measuring string length, string concatenation, accessing individual characters, extracting substrings, comparing strings, and sorting.
Library Functions: The string.h library provides pre-implemented functions for common string manipulations, reducing the need to write custom code.
Practical Examples: Code examples provided illustrate how to manipulate strings, including copying, concatenation, and reading inputs that may contain spaces.
Applications of Strings: Practical applications include problems like calculating complementary DNA strands and checking whether a phrase is a pangram.
Recommended Exercises: A list of exercises is offered for practice, targeting different aspects of string operations and manipulation.
Additional Resources: Links to external documentation and ASCII tables are available for further learning.
Related queries:

What are the main operations possible with strings in C?
How does the `string.h` library facilitate string manipulation in C?
Can you explain how to determine if a string is a pangram in C?

Key Takeaway
Structs enable the grouping of related data of different types into a single composite data type, facilitating structured programming and data management.

Summary
Introduction to Structs:

Structs, also known as records, allow the grouping of related data of different types.
Examples include personal information (name, age, gender) and game character attributes.
Declaration of Structs:

A new data type is defined using struct, which can include various fields with different data types.
Struct instances can be declared directly or using typedef for easier instantiation.
Example structure for a monster includes attributes like name, level, and stats.
Accessing Struct Fields:

Individual fields within a struct can be accessed using the dot operator (.) for instances.
Example code walk-through demonstrates how to gather input for multiple monster instances.
Pointers to Structs:

Structs can be manipulated using pointers, allowing for functions to alter the contained data.
Access can be done either by dereferencing pointers or using the arrow operator (->).
Structs with Functions:

Examples illustrate the use of structs in functions, such as managing employee records.
Code snippets show how structs can be used to gather and print employee information.
Memory Layout of Structs:

Structs are stored in contiguous memory locations, similar to arrays, with attributes aligned according to their data types.
Practical Implementations:

Multiple practical examples provide insight into defining structs, using arrays of structs, and sorting/processing involving data structures.
Related queries:

What is the purpose of using structs in programming?
How do you declare and access fields in a struct?
What are the memory considerations when using structs?

Key Takeaway
Understanding file manipulation in C is essential for managing data persistence beyond program execution, particularly with text files.

Summary
Introduction to File Handling: Memory is volatile; hence, files are used to store information persistently even after program execution.
File Definition: Files serve as organized data entities within non-volatile memory. The operating system manages these files, treating them as streams of bytes.
File Types:
Text Files: Each byte represents a character; they are human-readable but occupy more space.
Binary Files: Data is stored byte by byte as it exists in memory; harder to read but more storage efficient.
File Operations in C:
Files are managed using pointers (e.g., FILE* fd).
The fopen() function is used to open files, requiring the file name and access mode.
Opening Modes:
"r": Read
"w": Write
"a": Append
"r+": Read and Write
"w+": Create or overwrite and read/write
"a+": Append and read
File Closing: Critical for freeing resources and saving changes with fclose().
Positioning in Files: The current position in a file can be managed using functions like rewind(), ftell(), and fseek().
Reading Data: Employ fscanf(), fgetchar(), and fgets() to read data from text files.
Writing Data: Use fprintf() to write data back to text files.
Common File Opening Errors: Issues such as file non-existence or permission restrictions can prevent successful file access.
Importance of Proper Closure: Ensures all operations in the buffer are written to the file, preventing data loss upon program termination.
Related queries:

What are the different modes for opening files in C?
How do you read and write text files in C?
What common errors occur while opening files in C?

Key Takeaway
Understanding and working with binary files in programming allows for efficient data storage and retrieval, particularly for complex data types.

Summary
Files and Their Types: Files are abstractions used for non-volatile data storage. They can be categorized as text or binary.
Binary Files: Binary files consist of a sequence of bytes, where each byte can represent various data types depending on the creator's specifications. They are less readable by humans compared to text files.
Advantages of Binary Files:
Ability to save data exactly as it is in memory.
Support for storing complex data structures such as arrays and structs.
Binary File Visualization: Tools like WinHex (for Windows) and Linux commands (hexdump or xxd) help visualize binary file content in hexadecimal form, though interpretation must be manual.
Opening Binary Files: Similar to text files but requires a 'b' in the mode when using the fopen() function. Modes include:
"rb" for reading
"wb" for writing
"ab" for appending
"r+b", "w+b", "a+b" for read/modifying in various combinations.
Reading and Writing:
fread() and fwrite() are functions used for reading and writing binary files, taking parameters such as pointer buffer, size, count, and file stream.
Example code demonstrates how to use these functions with structs to write and read data.
Error Handling and State Checking: After operations, it is advisable to check the status of the file to handle errors using feof() and ferror() functions.
Practical Examples: Simple examples depict reading from and writing to binary files containing student records using predefined structs.
Related queries:

What are the key differences between text and binary files?
How do you check for errors while reading or writing to a binary file?
Can binary files store complex data types and how?

Key Takeaway
Recursive functions are powerful tools for solving problems defined by smaller instances of themselves but require careful management to avoid issues like stack overflow.

Summary
Functions can be categorized into regular and recursive types.
Recursive functions call themselves, making them useful for solving recursive problems, which can be defined using smaller instances of themselves.
Each recursive function must have a base case to prevent infinite recursion.
The factorial function is a classic example of recursion, with its definition utilizing itself: n! = n * (n-1)!.
The stack execution model is crucial for understanding recursion; each recursive call creates a new layer in the memory stack.
Important aspects of stack execution:
Each function call has its own parameters and local variables.
The function at the top of the stack is currently executing, while others wait in line.
Overuse of recursion can lead to stack overflow, highlighting the importance of the base case in recursive design.
Recursive solutions can be elegant and straightforward, but they are often less efficient compared to iterative solutions due to overhead.
Examples of recursive functions include:
Power calculation: pow_recursivo(int x, int n).
String reversal: inverter_string(char nome[], char aux[], int n).
Binary search: binary_search(int v[], int x, int L, int R).
Recommended exercises focus on implementing recursive solutions to various problems, enhancing understanding and application of recursion.
Related queries:

What is a recursive function?
How does the execution stack work in recursion?
What are some common pitfalls of using recursion?

Key Takeaway
Understanding pointers in programming is essential, as they are crucial for memory management and variable reference.

Summary
Memory Overview: The page discusses RAM as the primary storage for executing programs and storing their variables.
Memory Size: Explained how memory size is determined by the type of processor (x86 or x64) and its addressing capabilities.
Usage of Memory: Describes the allocation of memory for variables and how data is read and written as bytes.
Types of Variables: Introduces how variables are stored as bits in memory and how they are interpreted based on their types.
Pointer Type: Defines pointers as variables that store memory addresses, demonstrating the syntactic structure to declare pointers in C (e.g., int* ip).
Void Pointers: Explains the special void* type which can reference any data type and the concept of pointers to pointers.
Pointer Arithmetic: Discusses referencing and dereferencing using the & (address-of) and * (dereference) operators in C.
Pointer Functionality: Highlights how pointers can help access variable values directly through memory addresses, without referencing variable names directly.
Extra Materials: Includes a conversion table between decimal, hexadecimal, and binary systems.
Related queries:

What are the differences between pointers and normal variables in C?
How do you declare a pointer to a void type?
What is the significance of dereferencing a pointer in C programming?


## Professors Feedback 👨‍🏫
Being real, the lack of professionalism of both teachers is something apart. *Carla Castanho* doesn't know how to teach, I guess the last time she coded in *C* was 20 years ago (not even joking), the peak of her class is a slide reading (if she goes to the class). *Franklin Ned* is a little better, but he's not good either. He knows how to teach, but doesn't seem like he wants. May leave the class earlier to go have some *pastel* and sugarcane juice. In the other hand, others students say that *Vinícius Ruela* and *Ishikawa* are good teachers.
## Contributing 🤝
*Do you feel that something is missing?*
Open an issue or a pull request and help me make a better repo for our new freshmen!
## Extras 🎁
- [link](https://carlacastanho.github.io/Material-de-APC/) to Carla's site.
- [link](https://www.onlinegdb.com/online_c_compiler) to a online *C* compiler.
- [link](https://www.youtube.com/playlist?list=PL8iN9FQ7_jt4DJbeQqv--jpTy-2gTA3Cp) to a complete playlist of *C language* on youtube. (*it's in portuguese*)
- [link](https://stackoverflow.com/) to Stack *Overflow*, where you can find answers to your questions.
- [link](https://www.classcentral.com/report/cs50-free-certificate/) to an article about *CS50* (*if you are completely raw to coding I recommend taking a look. It's free!*)
    - [link](https://cs50.harvard.edu/ap/2025/syllabus/) to the course.
    - [link](https://cs50.harvard.edu/ap/2025/curriculum/) to the course curriculum.