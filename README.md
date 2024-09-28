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