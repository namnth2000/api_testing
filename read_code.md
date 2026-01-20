## Câu 1

```js
let doorClosed = false;

if (doorClosed) {
    console.log("RUN");
} else {
    console.warn("DOOR OPEN");
}
```

In ra gì?

---

## Câu 2

```js
let childLock = LOCK.ON;

if (childLock === LOCK.ON) {
    console.warn("LOCKED");
} else {
    console.log("UNLOCKED");
}
```

In ra gì?

---

## Câu 3

```js
let temperature = 220;

if (temperature > 200) {
    console.error("OVERHEAT");
} else {
    console.log("NORMAL");
}
```

In ra gì?

---

## Câu 4

```js
let power = POWER.ON;
let filterClean = false;

if ((power === POWER.ON) && (filterClean === true)) {
    console.log("COOLING");
} else {
    console.warn("CHECK FILTER");
}
```

In ra gì?

---

## Câu 5

```js
let childLock = LOCK.OFF;
let doorClosed = true;

if ((childLock === LOCK.OFF) && (doorClosed === true)) {
    console.log("START WASH");
} else {
    console.warn("BLOCKED");
}
```

In ra gì?

---

## Câu 6

```js
let recipe = null;

if (recipe !== null) {
    console.log("START BAKE");
} else {
    console.warn("NO RECIPE");
}
```

In ra gì?

---

## Câu 7

```js
function shutdown() {
    console.error("SHUTDOWN");
}

function cook() {
    console.log("COOKING");
}

let temperature = 180;
let overheat = false;

if ((temperature > 200) || (overheat === true)) {
    shutdown();
} else {
    cook();
}
```

In ra gì?

---

## Câu 8

```js
let power = POWER.ON;
let mode = MODE.COOL;
let windowOpen = true;
let overheat = false;

if ((power === POWER.ON) && ((mode === MODE.COOL) || (windowOpen === false)) && (overheat === false)) {
    console.log("AC RUNNING");
} else {
    console.warn("AC STOP");
}
```

In ra gì?

---

## Câu 9

```js
function bake() {
    console.log("BAKING");
}

function blocked() {
    console.warn("BLOCKED");
}

let power = POWER.ON;
let mode = MODE.BAKE;
let childLock = LOCK.ON;

if ((power === POWER.ON) && (childLock === LOCK.OFF)) {
    bake();
} else {
    blocked();
}
```

In ra gì?

---

## Câu 10

```js
function alarm() {
    console.error("ALARM");
}

function wait() {
    console.warn("WAIT");
}

function start() {
    console.log("START");
}

let power = POWER.ON;
let childLock = LOCK.OFF;
let doorClosed = true;
let temperature = 210;
let overheat = temperature > 200;
let mode = MODE.WASH;

if ((power !== POWER.ON) || (overheat === true)) {
    alarm();
} else if ((childLock === LOCK.ON) || (doorClosed === false)) {
    wait();
} else if (mode === MODE.WASH) {
    start();
} else {
    wait();
}
```

In ra gì?

---

## ĐÁP ÁN

1. DOOR OPEN
2. LOCKED
3. OVERHEAT
4. CHECK FILTER
5. START WASH
6. NO RECIPE
7. COOKING
8. AC RUNNING
9. BLOCKED
10. ALARM

---
