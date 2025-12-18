🔹 SIMPLE WAY: Use separate variables for each operation

---

## 🔹 SIMPLE WAY: Use separate variables for each operation

### ✅ Full Working Program (Addition, Subtraction, Multiplication, Division, Modulus)

```c
#include <stdio.h>

int main() {
    int a = 5, b = 3;

    int add, sub, mul, div, mod;

    add = a + b;   // Addition
    sub = a - b;   // Subtraction
    mul = a * b;   // Multiplication
    div = a / b;   // Division
    mod = a % b;   // Modulus

    printf("Addition: %d\n", add);
    printf("Subtraction: %d\n", sub);
    printf("Multiplication: %d\n", mul);
    printf("Division: %d\n", div);
    printf("Modulus: %d\n", mod);

    return 0;
}
```

---

## 🔹 OUTPUT (IMPORTANT)

```
Addition: 8
Subtraction: 2
Multiplication: 15
Division: 1
Modulus: 2
```

👉 **Note:**
`5 / 3 = 1` because **int division** removes decimal part.

---

## 🔹 IF YOU WANT DECIMAL DIVISION (VERY IMPORTANT)

Use `float`:

```c
#include <stdio.h>

int main() {
    int a = 5, b = 3;
    float div;

    div = (float)a / b;
    printf("Division: %.2f", div);

    return 0;
}
```

### Output:

```
Division: 1.67
```

---

## 🔹 SHORT METHOD (WITHOUT EXTRA VARIABLES)

```c
#include <stdio.h>

int main() {
    int a = 5, b = 3;

    printf("Add: %d\n", a + b);
    printf("Sub: %d\n", a - b);
    printf("Mul: %d\n", a * b);
    printf("Div: %d\n", a / b);
    printf("Mod: %d\n", a % b);

    return 0;
}
```

---

## 🧠 EXAM TIP (REMEMBER THIS)

* `+ - * / %` → Arithmetic operators
* `/` with `int` → no decimal
* `%` → only works with `int`
* Use `float` for decimal answers

---
