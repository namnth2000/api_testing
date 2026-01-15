# ĐỀ 1

### Câu 1

```c
int x = 5;

if (x > 5) {
    doTaskA();
} else {
    doTaskB();
}
```

**Câu hỏi:**
Hàm nào sẽ được thực hiện?

---

### Câu 2

```c
int temp = 80;

if (temp > 50) {
    if (temp > 100) {
        printf("High\n");
    } else {
        printf("Normal\n");
    }
} else {
    printf("Low\n");
}
```

**Câu hỏi:**
Kết quả in ra là gì?

---

### Câu 3

```c
int door = 1;
int power = 0;
if (door == 1 && power == 1) {
    printf("Start\n");
} else if (door == 1) {
    printf("No Power\n");
} else {
    printf("Door Open\n");
}
```

**Câu hỏi:**
Kết quả in ra là gì?

---

### Câu 4

```cpp
int a = 10;

if (a > 5) {
    if (a > 20)
        cout << "Big\n";
    else
        cout << "Medium\n";
} else {
    cout << "Small\n";
}
```

**Câu hỏi:**
Kết quả in ra là gì?

---

### Câu 5

```cpp
int level = 2;

if (level == 1)
    cout << "Low\n";
else if (level == 2)
    cout << "Mid\n";
else
    cout << "High\n";
```

**Câu hỏi:**
Chương trình in ra gì?

---

### Câu 6

```python
x = 1

if x > 0:
    print("Positive")
else:
    print("Non-positive")
```

**Câu hỏi:**
Kết quả in ra là gì?

---

### Câu 7

```python
x = 5

if x > 10:
    print("High")
elif x > 3:
    print("Mid")
else:
    print("Low")
```

**Câu hỏi:**
Chương trình in ra gì?

---

# ĐÁP ÁN

1. doTaskB
2. Normal
3. No Power
4. Medium
5. Mid
6. Non-positive
7. Mid

---
<br>
<br>
<br>
---

# ĐỀ 2

### Câu 1

```c
#include <stdio.h>

void A() { printf("A\n"); }
void B() { printf("B\n"); }

int main() {
    int door = 0;
    int power = 1;

    if (door && power || power) {
        A();
    } else {
        B();
    }
    return 0;
}
```

**Câu hỏi:**
Hàm nào được gọi?

---

### Câu 2

```c
#include <stdio.h>

int main() {
    int temp = 95;
    int fan = 1;

    if (temp > 50) {
        if (temp > 100 || fan == 0) {
            printf("ALERT\n");
        } else {
            printf("RUN\n");
        }
    } else {
        printf("STOP\n");
    }
    return 0;
}
```

**Câu hỏi:**
Kết quả in ra là gì?

---

### Câu 3

```c
#include <stdio.h>

int main() {
    int a = 1;
    int b = 0;
    int c = 1;

    if (a)
        if (b || c)
            printf("X\n");
        else
            printf("Y\n");
    else
        printf("Z\n");

    return 0;
}
```

**Câu hỏi:**
Chương trình in ra gì?

---

### Câu 4

```c
#include <stdio.h>

int main() {
    int door = 1;
    int lock = 0;
    int power = 1;

    if (door && lock) {
        printf("START\n");
    } else if (door && power) {
        printf("CHECK LOCK\n");
    } else if (power) {
        printf("OPEN DOOR\n");
    } else {
        printf("NO POWER\n");
    }
    return 0;
}
```

**Câu hỏi:**
In ra gì?

---

### Câu 5

```cpp
#include <iostream>
using namespace std;

void start() { cout << "START\n"; }
void stop()  { cout << "STOP\n"; }

int main() {
    int sensor = 1;
    int error = 0;

    if (sensor) {
        if (error)
            stop();
        else
            start();
    } else {
        stop();
    }
    return 0;
}
```

**Câu hỏi:**
Hàm nào được gọi?

---

### Câu 6

```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 0;
    int b = 1;
    int c = 0;

    if (a && b || c) {
        cout << "TRUE\n";
    } else {
        cout << "FALSE\n";
    }
    return 0;
}
```

**Câu hỏi:**
In ra gì?

---

### Câu 7

```cpp
#include <iostream>
using namespace std;

int main() {
    int mode = 2;
    int power = 0;

    if (mode == 1 && power) {
        cout << "MODE1\n";
    } else if (mode == 2 || power) {
        cout << "MODE2\n";
    } else {
        cout << "OFF\n";
    }
    return 0;
}
```

**Câu hỏi:**
Kết quả in ra là gì?

---

### Câu 8

```python
a = False
b = True
c = False

if a and b or c:
    print("YES")
else:
    print("NO")
```

**Câu hỏi:**
In ra gì?

---

### Câu 9

```python
def run(door, power, error):
    if door:
        if power and not error:
            print("RUN")
        else:
            print("WAIT")
    else:
        print("OPEN")

run(True, True, False)
```

**Câu hỏi:**
Kết quả in ra là gì?

---

### Câu 10

```python
temp = 85
fan = True
alarm = False

if temp > 90 or alarm:
    print("ALERT")
elif temp > 60 and fan:
    print("COOL")
elif temp > 60:
    print("HOT")
else:
    print("OK")
```

**Câu hỏi:**
In ra gì?

---

# ĐÁP ÁN

1. A
2. RUN
3. X
4. CHECK LOCK
5. start()
6. FALSE
7. MODE2
8. NO
9. RUN
10. COOL

---

