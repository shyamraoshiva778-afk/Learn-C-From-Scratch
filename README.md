Perfect 👍 Let’s start **C Language from zero (Beginner level)** in a very simple way.

---

## 🔰 What is C Language?

* C is a **programming language** created by **Dennis Ritchie**.
* It is used to build **operating systems**, **software**, **games**, and **embedded systems**.
* Easy to learn basics, very powerful.

---

## 🧠 What You Need Before Starting

* Basic computer knowledge
* No coding experience needed ✅

---

## 🪜 Step-by-Step Learning Plan (Beginner)

### ✅ Step 1: Basic Structure of C Program

Every C program looks like this:

```c
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```

📌 Explanation:

* `#include <stdio.h>` → for input & output
* `int main()` → program starts here
* `printf` → prints output
* `return 0;` → end of program

---

### ✅ Step 2: Data Types

Used to store values.

```c
int a = 10;        // integer
float b = 3.5;    // decimal
char c = 'A';     // character
```

---

### ✅ Step 3: Variables

Used to store data.

```c
int age = 20;
printf("%d", age);
```

---

### ✅ Step 4: Input from User

```c
int num;
scanf("%d", &num);
```

👉 `scanf` takes input
👉 `&` is important

---

### ✅ Step 5: Operators

* `+` Addition
* `-` Subtraction
* `*` Multiplication
* `/` Division

Example:

```c
int a = 10, b = 5;
int sum = a + b;
printf("%d", sum);
```

---

### ✅ Step 6: If-Else Statement

```c
int age = 18;
if(age >= 18) {
    printf("Adult");
} else {
    printf("Not Adult");
}
```

---

### ✅ Step 7: Loops

#### 🔁 For Loop

```c
for(int i = 1; i <= 5; i++) {
    printf("%d ", i);
}
```

#### 🔁 While Loop

```c
int i = 1;
while(i <= 5) {
    printf("%d ", i);
    i++;
}
```

---

### ✅ Step 8: Functions

```c
void hello() {
    printf("Welcome to C");
}
```

---

## 🛠️ Where to Practice C?

* **Turbo C** (Old but simple)
* **Code::Blocks**
* **Online Compilers** (easy for beginners)

---

Nice 👍
Then let’s begin **C Language – LESSON 1 (For Absolute Beginners)**

---

## 📘 LESSON 1: Your First C Program

### ✅ Goal of this lesson

* Understand basic C program
* Print text on screen

---

## 🧾 C Program: Hello World

```c
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```

---

## 🔍 Line-by-Line Explanation

### 🔹 `#include <stdio.h>`

* Tells the compiler to include **Standard Input Output**
* Needed for `printf()` and `scanf()`

---

### 🔹 `int main()`

* Program execution **starts from here**
* `int` means it returns a number

---

### 🔹 `{ }`

* Curly braces define **start and end** of program

---

### 🔹 `printf("Hello World");`

* Prints text on the screen
* Text must be inside **double quotes**

---

### 🔹 `return 0;`

* Ends the program
* `0` means program executed successfully

---

## ▶️ Output

```
Hello World
```

---

## ✅ Important Rules (Remember This)

* Every statement ends with `;`
* C is **case-sensitive**
* Use double quotes `" "` for text
* Program must have `main()`

---

## 📝 Practice (Very Important ❗)

Try to write programs to:

1. Print your **name**
2. Print **Welcome to C language**

Example:

```c
printf("My Name is Kabali");
```

---

# 📘 C LANGUAGE – LESSON 2 

## 🔹 What is a Variable?

A **variable** is a container to store a value.

Example:

```c
int age = 20;
```

* `int` → data type
* `age` → variable name
* `20` → value

---

## 🔹 Rules for Variable Names

✅ Can use letters, numbers, `_`
❌ Cannot start with a number
❌ No spaces

✅ Valid:

```c
age, total_marks, num1
```

❌ Invalid:

```c
1age, total marks
```

---

## 🔹 Data Types in C (Basic)

| Data Type | Meaning          | Example |
| --------- | ---------------- | ------- |
| `int`     | Whole numbers    | 10, -5  |
| `float`   | Decimal numbers  | 5.6     |
| `char`    | Single character | 'A'     |

---

## 🔹 Example 1: Using All Data Types

```c
#include <stdio.h>

int main() {
    int age = 21;
    float height = 5.8;
    char grade = 'A';

    printf("Age: %d\n", age);
    printf("Height: %.1f\n", height);
    printf("Grade: %c\n", grade);

    return 0;
}
```

---

## 🔹 Format Specifiers (VERY IMPORTANT)

| Type               | Specifier |
| ------------------ | --------- |
| int                | `%d`      |
| float              | `%f`      |
| float (2 decimals) | `%.2f`    |
| char               | `%c`      |

---

## 🔹 Example 2: Taking Input from User

```c
#include <stdio.h>

int main() {
    int age;
    float height;

    printf("Enter age: ");
    scanf("%d", &age);

    printf("Enter height: ");
    scanf("%f", &height);

    printf("Age = %d\n", age);
    printf("Height = %.2f\n", height);

    return 0;
}
```

---

## 🧠 IMPORTANT RULES (MEMORIZE)

### ✅ `scanf`

* Always use `&`
* Never use `\n`

### ✅ `printf`

* Use correct format specifier
* `\n` for new line is OK

---

## 🧪 Small Practice (Try Yourself)

1️⃣ Take two integers → print sum
2️⃣ Take a float → print with 2 decimals
3️⃣ Take a character → print it

---
Perfect 👍
Let’s do **LESSON 3 – OPERATORS** again, **clear + revision style**.

---

# 📘 C LANGUAGE – LESSON 3: OPERATORS

Operators are used to **perform operations** on variables and values.

---

## 🔹 1️⃣ Arithmetic Operators

| Operator | Meaning        | Example |
| -------- | -------------- | ------- |
| `+`      | Addition       | `a + b` |
| `-`      | Subtraction    | `a - b` |
| `*`      | Multiplication | `a * b` |
| `/`      | Division       | `a / b` |
| `%`      | Remainder      | `a % b` |

---

### ✅ Example 1: All Arithmetic Operations

```c
#include <stdio.h>

int main() {
    int a, b;

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    printf("Addition = %d\n", a + b);
    printf("Subtraction = %d\n", a - b);
    printf("Multiplication = %d\n", a * b);
    printf("Division = %d\n", a / b);
    printf("Remainder = %d\n", a % b);

    return 0;
}
```

---

## ⚠️ Important Rule (VERY IMPORTANT)

* `%` works **only with int**
* `int / int = int`

Example:

```c
5 / 2 = 2   // not 2.5
```

---

## 🔹 2️⃣ Relational (Comparison) Operators

Used in **if conditions**.

| Operator | Meaning          |
| -------- | ---------------- |
| `==`     | Equal            |
| `!=`     | Not equal        |
| `>`      | Greater          |
| `<`      | Less             |
| `>=`     | Greater or equal |
| `<=`     | Less or equal    |

### ✅ Example

```c
if(a > b) {
    printf("A is greater");
}
```

---

## 🔹 3️⃣ Logical Operators

Used to combine conditions.

| Operator | Meaning |   |    |
| -------- | ------- | - | -- |
| `&&`     | AND     |   |    |
| `        |         | ` | OR |
| `!`      | NOT     |   |    |

### ✅ Example

```c
if(age >= 18 && age <= 60) {
    printf("Eligible");
}
```

---

## 🔹 4️⃣ Increment / Decrement Operators

```c
int x = 5;

x++;   // x = 6
x--;   // x = 5
```

### Difference

```c
i++;   // post-increment
++i;   // pre-increment
```

---

## 🔹 5️⃣ Assignment Operators

| Operator | Example  |
| -------- | -------- |
| `=`      | `a = 10` |
| `+=`     | `a += 5` |
| `-=`     | `a -= 2` |
| `*=`     | `a *= 3` |

Example:

```c
a += 5;  // a = a + 5
```

---

## 🧪 Practice Questions

1️⃣ Add, subtract, multiply two numbers
2️⃣ Check even or odd using `%`
3️⃣ Check largest of two numbers
4️⃣ Check eligible to vote using logical operators

---

## 🧠 Quick Tip

* Operators + if + loops = real programming 💪

---

# 📘 C LANGUAGE – LESSON 4: IF–ELSE

## 🔹 What is if–else?

`if–else` is used to **make decisions** in a program.

👉 *If a condition is true → do one thing*
👉 *Else → do another thing*

---

## 🔹 Basic Syntax

```c
if(condition) {
    // code if condition is true
} else {
    // code if condition is false
}
```

---

## 🔹 Example 1: Check Even or Odd

```c
#include <stdio.h>

int main() {
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    if(num % 2 == 0) {
        printf("Even number");
    } else {
        printf("Odd number");
    }

    return 0;
}
```

---

## 🔹 Example 2: Check Eligible to Vote

```c
#include <stdio.h>

int main() {
    int age;

    printf("Enter age: ");
    scanf("%d", &age);

    if(age >= 18) {
        printf("Eligible to vote");
    } else {
        printf("Not eligible to vote");
    }

    return 0;
}
```

---

## 🔹 Example 3: Positive, Negative or Zero (if–else-if)

```c
#include <stdio.h>

int main() {
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    if(num > 0) {
        printf("Positive");
    } else if(num < 0) {
        printf("Negative");
    } else {
        printf("Zero");
    }

    return 0;
}
```

---

## 🔹 Example 4: Find Largest of Two Numbers

```c
#include <stdio.h>

int main() {
    int a, b;

    scanf("%d %d", &a, &b);

    if(a > b) {
        printf("A is greater");
    } else {
        printf("B is greater");
    }

    return 0;
}
```

---

## 🔹 Comparison Operators (REVISION)

| Operator | Meaning          |
| -------- | ---------------- |
| `==`     | Equal            |
| `!=`     | Not equal        |
| `>`      | Greater          |
| `<`      | Less             |
| `>=`     | Greater or equal |
| `<=`     | Less or equal    |

⚠️ **Very common mistake**
❌ `if(a = b)`
✅ `if(a == b)`

---

## 🔹 Nested if (if inside if)

```c
if(age >= 18) {
    if(age <= 60) {
        printf("Working age");
    }
}
```

---

## 🧪 Practice Questions (Try Yourself)

1️⃣ Check **pass or fail** (marks ≥ 35)
2️⃣ Check **largest of three numbers**
3️⃣ Check **leap year**
4️⃣ Check **grade** using marks

---

## 🧠 Easy Rule to Remember

* `if` → first condition
* `else if` → second condition
* `else` → default case

---

# 📘 C LANGUAGE – LESSON 5: SWITCH CASE

## 🔹 What is `switch case`?

`switch case` is used when you have **many choices** based on **one value**.

👉 Best alternative to **multiple if–else**.

---

## 🔹 Basic Syntax

```c
switch(expression) {
    case value1:
        // code
        break;

    case value2:
        // code
        break;

    default:
        // code
}
```

---

## 🔹 Important Keywords

* `switch` → checks the value
* `case` → matches the value
* `break` → stops execution
* `default` → runs if no case matches

---

## 🔹 Example 1: Simple Switch Case

```c
#include <stdio.h>

int main() {
    int num;

    printf("Enter a number (1-3): ");
    scanf("%d", &num);

    switch(num) {
        case 1:
            printf("One");
            break;
        case 2:
            printf("Two");
            break;
        case 3:
            printf("Three");
            break;
        default:
            printf("Invalid number");
    }

    return 0;
}
```

---

## 🔹 Example 2: Calculator using Switch

```c
#include <stdio.h>

int main() {
    int a, b;
    char op;

    printf("Enter operator (+ - * /): ");
    scanf(" %c", &op);

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    switch(op) {
        case '+':
            printf("Result = %d", a + b);
            break;
        case '-':
            printf("Result = %d", a - b);
            break;
        case '*':
            printf("Result = %d", a * b);
            break;
        case '/':
            printf("Result = %d", a / b);
            break;
        default:
            printf("Invalid operator");
    }

    return 0;
}
```

---

## 🔹 Example 3: Day Name Program

```c
#include <stdio.h>

int main() {
    int day;

    printf("Enter day number (1-7): ");
    scanf("%d", &day);

    switch(day) {
        case 1: printf("Monday"); break;
        case 2: printf("Tuesday"); break;
        case 3: printf("Wednesday"); break;
        case 4: printf("Thursday"); break;
        case 5: printf("Friday"); break;
        case 6: printf("Saturday"); break;
        case 7: printf("Sunday"); break;
        default: printf("Invalid day");
    }

    return 0;
}
```

---

## ⚠️ VERY IMPORTANT RULES

1️⃣ `switch` works with:

* `int`
* `char`

❌ Not with `float`

2️⃣ Always use `break`

* Without `break`, execution continues to next case

---

## 🔥 Example: Without `break` (Fall-through)

```c
switch(1) {
    case 1: printf("One ");
    case 2: printf("Two ");
    case 3: printf("Three ");
}
```

### Output:

```
One Two Three
```

---

## 🧪 Practice Tasks

1️⃣ Menu-driven program
2️⃣ Vowel or consonant checker
3️⃣ Month name program
4️⃣ Simple ATM menu

---

## 🧠 When to Use What?

* Few conditions → **if–else**
* Many fixed choices → **switch case**

---
## 🔁 LESSON 6 – LOOPS IN C

### 📌 What is a Loop?

A **loop** is used when you want to **repeat the same block of code multiple times** without writing it again and again.

👉 Example:
Printing numbers from 1 to 10
Printing a table
Repeating input/output

---

## 🔹 Types of Loops in C

C language has **3 main loops**:

1. **while loop**
2. **do–while loop**
3. **for loop**

---

## 1️⃣ while Loop

### 📌 Syntax

```c
while(condition) {
    // code to repeat
}
```

### 📌 How it works

* First checks the **condition**
* If condition is **true**, code runs
* Repeats until condition becomes **false**

### ✅ Example: Print 1 to 5

```c
#include <stdio.h>

int main() {
    int i = 1;

    while(i <= 5) {
        printf("%d\n", i);
        i++;
    }

    return 0;
}
```

📌 **Important**

* If condition is false initially → loop will **not run**
* Increment/decrement is **mandatory** to avoid infinite loop

---

## 2️⃣ do–while Loop

### 📌 Syntax

```c
do {
    // code to repeat
} while(condition);
```

⚠️ Semicolon `;` is **required**

### 📌 How it works

* Executes code **at least once**
* Condition is checked **after execution**

### ✅ Example

```c
#include <stdio.h>

int main() {
    int i = 1;

    do {
        printf("%d\n", i);
        i++;
    } while(i <= 5);

    return 0;
}
```

📌 Even if condition is false, loop runs **one time**

---

## 🔍 while vs do–while

| Feature           | while       | do–while   |
| ----------------- | ----------- | ---------- |
| Condition check   | Before loop | After loop |
| Minimum execution | 0 times     | 1 time     |
| Semicolon         | ❌ No        | ✅ Yes      |

---

## 3️⃣ for Loop

### 📌 Syntax

```c
for(initialization; condition; increment/decrement) {
    // code
}
```

### 📌 Best for

* Known number of repetitions
* Tables
* Counters

### ✅ Example: Print 1 to 5

```c
#include <stdio.h>

int main() {
    int i;

    for(i = 1; i <= 5; i++) {
        printf("%d\n", i);
    }

    return 0;
}
```

📌 Everything is written in **one line**, so it looks clean.

---

## 🧮 Example: Table of a Number

```c
#include <stdio.h>

int main() {
    int num, i;

    printf("Enter number: ");
    scanf("%d", &num);

    for(i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", num, i, num * i);
    }

    return 0;
}
```

---

## ❌ Infinite Loop (Danger)

A loop that **never stops**.

### Example

```c
while(1) {
    printf("Hello");
}
```

📌 Happens when:

* Condition never becomes false
* Increment/decrement missing

---

## 🧠 When to Use Which Loop?

| Situation              | Best Loop |
| ---------------------- | --------- |
| Condition-based        | while     |
| Must run at least once | do–while  |
| Fixed repetitions      | for       |

---

## ✅ Summary

* Loops save time and code
* 3 loops: while, do–while, for
* Always control condition
* Avoid infinite loops




