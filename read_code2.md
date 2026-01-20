## CÂU 11

```js
for (let i = 0; i < 3; i++) {
    console.log("WASH");
}
```

In ra gì?

---

## CÂU 12

```js
for (let temp = 18; temp <= 20; temp++) {
    if (temp === 19) {
        console.log("TARGET");
    } else {
        console.log("ADJUST");
    }
}
```

In ra gì?

---

## CÂU 13

```js
for (let temperature = 180; temperature <= 220; temperature += 20) {
    if (temperature > 200) {
        console.error("OVERHEAT");
    } else {
        console.log("NORMAL");
    }
}
```

In ra gì?

---

## CÂU 14

```js
let childLock = LOCK.ON;

for (let step = 1; step <= 2; step++) {
    if (childLock === LOCK.ON) {
        console.warn("LOCKED");
    } else {
        console.log("STEP " + step);
    }
}
```

In ra gì?

---

## CÂU 15

```js
let time = 3;

while (time > 0) {
    console.log("HEATING");
    time--;
}
```

In ra gì?

---

## CÂU 16

```js
let temperature = 180;

while (temperature <= 240) {
    if (temperature > 200) {
        console.error("OVERHEAT");
        break;
    }
    console.log("COOK");
    temperature += 10;
}
```

In ra gì?

---

## CÂU 17

```js
for (let minute = 1; minute <= 4; minute++) {
    if (minute === 3) {
        continue;
    }
    console.log("RUN " + minute);
}
```

In ra gì?

---

## CÂU 18

```js
let program = null;
let retry = 0;

while (retry < 2) {
    if (program === null) {
        console.warn("NO PROGRAM");
    } else {
        console.log("START");
    }
    retry++;
}
```

In ra gì?

---

## CÂU 19

```js
let power = POWER.ON;
let childLock = LOCK.OFF;

for (let attempt = 1; attempt <= 3; attempt++) {
    if ((power !== POWER.ON) || (childLock === LOCK.ON)) {
        console.warn("BLOCKED");
    } else if (attempt === 2) {
        console.log("RETRY");
    } else {
        console.log("RUN");
    }
}
```

In ra gì?

---

## CÂU 20

```js
let temperature = 190;
let power = POWER.ON;

while (power === POWER.ON) {
    let overheat = temperature > 200;

    if (overheat === true) {
        console.error("ALARM");
        break;
    } else {
        console.log("HEATING");
    }

    temperature += 10;
}
```

In ra gì?

---

## ĐÁP ÁN

11.

WASH
WASH
WASH

12.

ADJUST
TARGET
ADJUST

13.

NORMAL
NORMAL
OVERHEAT

14.

LOCKED
LOCKED

15.

HEATING
HEATING
HEATING

16.

COOK
COOK
OVERHEAT

17.

RUN 1
RUN 2
RUN 4

18.

NO PROGRAM
NO PROGRAM

19.

RUN
RETRY
RUN

20.

HEATING
HEATING
ALARM

---

### Giải thích `break` và `continue`

* `break` dừng loop ngay (câu 16, 20)
* `continue` bỏ qua 1 vòng (câu 17)
