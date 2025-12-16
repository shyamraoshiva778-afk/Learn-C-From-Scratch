

## 🧱 LESSON 7 – `break` and `continue`

These keywords are used **inside loops** (`for`, `while`, `do–while`) to **control the flow** of execution.

---

## 1️⃣ `break` Statement

### 📌 What is `break`?

`break` is used to **immediately stop a loop** and come **outside the loop**.

👉 When C sees `break`, the loop ends instantly.

---

### 📌 Syntax

```c
break;
```

---

### ✅ Example: Stop loop at 5

```c
#include <stdio.h>

int main() {
    int i;

    for(i = 1; i <= 10; i++) {
        if(i == 5) {
            break;
        }
        printf("%d\n", i);
    }

    return 0;
}
```

### 🖨 Output

```
1
2
3
4
```

📌 Loop stops when `i == 5`.

---

### ✅ `break` in `while` loop

```c
int i = 1;

while(i <= 10) {
    if(i == 7) {
        break;
    }
    printf("%d\n", i);
    i++;
}
```

---

### 📌 Use of `break`

* Exit loop early
* Stop on a condition
* Used in **switch case** also

---

## 2️⃣ `continue` Statement

### 📌 What is `continue`?

`continue` **skips the current iteration** and jumps to the **next loop cycle**.

👉 Loop does NOT end, only current step is skipped.

---

### 📌 Syntax

```c
continue;
```

---

### ✅ Example: Skip number 5

```c
#include <stdio.h>

int main() {
    int i;

    for(i = 1; i <= 10; i++) {
        if(i == 5) {
            continue;
        }
        printf("%d\n", i);
    }

    return 0;
}
```

### 🖨 Output

```
1
2
3
4
6
7
8
9
10
```

📌 Only `5` is skipped.

---

### ⚠️ `continue` in while loop (Important)

```c
int i = 0;

while(i < 5) {
    i++;

    if(i == 3) {
        continue;
    }

    printf("%d\n", i);
}
```

📌 Increment must come **before** `continue`, or infinite loop happens.

---

## 🔍 Difference: `break` vs `continue`

| Feature           | `break` | `continue` |
| ----------------- | ------- | ---------- |
| Stops loop        | ✅ Yes   | ❌ No       |
| Skips iteration   | ❌ No    | ✅ Yes      |
| Goes outside loop | ✅ Yes   | ❌ No       |
| Used in switch    | ✅ Yes   | ❌ No       |

---

## 🧠 Real-Life Example

* **break** → Stop watching movie and leave theatre 🎬
* **continue** → Skip boring scene, keep watching ▶️

---

## ❌ Common Mistakes

❌ Forgetting increment before `continue`
❌ Using `continue` outside loop
❌ Expecting `continue` to stop loop

---

## ✅ Summary

* `break` → exits loop completely
* `continue` → skips current loop step
* Used for better control
* Very important for exams & logic

---
