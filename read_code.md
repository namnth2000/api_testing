## Câu 1

```js
let x = 1;

if (x > 0) {
    console.log("POSITIVE");
} else {
    console.log("NEGATIVE");
}
```

**Câu hỏi:**
In ra gì?

---

## Câu 2

```js
let ready = false;

if (ready) {
    console.log("READY");
} else {
    console.warn("NOT READY");
}
```

**Câu hỏi:**
In ra gì? (log hay warn?)

---

## Câu 3

```js
let power = POWER.OFF;

if (power === POWER.ON) {
    console.log("POWER ON");
} else {
    console.error("NO POWER");
}
```

**Câu hỏi:**
In ra gì? (log hay error?)

---

## Câu 4

```js
let power = POWER.ON;
let door = DOOR.CLOSED;

if ((power === POWER.ON) && (door === DOOR.CLOSED)) {
    console.log("START");
} else {
    console.warn("BLOCK");
}
```

**Câu hỏi:**
In ra gì?

---

## Câu 5

```js
let power = POWER.OFF;
let door = DOOR.OPEN;

if ((power === POWER.ON) || (door === DOOR.CLOSED)) {
    console.log("ALLOW");
} else {
    console.warn("DENY");
}
```

**Câu hỏi:**
In ra gì?

---

## Câu 6

```js
let config = null;

if (config) {
    console.log("HAS CONFIG");
} else {
    console.warn("NO CONFIG");
}
```

**Câu hỏi:**
In ra gì? Vì sao?

---

## Câu 7

```js
function run() {
    console.log("RUN");
}

function stop() {
    console.error("STOP");
}

let sensor = true;
let error = false;

if ((sensor === true) && (error === false)) {
    run();
} else {
    stop();
}
```

**Câu hỏi:**
Hàm nào được gọi và in ra gì?

---

## Câu 8

```js
let power = POWER.ON;
let door = DOOR.OPEN;
let mode = MODE.WASH;

if ((power === POWER.ON) && ((door === DOOR.CLOSED) || (mode === MODE.WASH))) {
    console.log("RUN");
} else {
    console.warn("BLOCK");
}
```

**Câu hỏi:**
In ra gì?

---

## Câu 9

```js
function startWash() {
    console.log("WASH");
}

function idle() {
    console.warn("IDLE");
}

let power = POWER.ON;
let mode = null;

if (power === POWER.ON) {
    if (mode === MODE.WASH) {
        startWash();
    } else {
        idle();
    }
} else {
    console.error("NO POWER");
}
```

**Câu hỏi:**
Hàm nào được gọi và in ra gì?

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
let door = DOOR.OPEN;
let mode = MODE.WASH;
let error = null;

if ((power !== POWER.ON) || (error === true)) {
    alarm();
} else if (door !== DOOR.CLOSED) {
    wait();
} else if (mode === MODE.WASH) {
    start();
} else {
    wait();
}
```

**Câu hỏi:**
Hàm nào được gọi và in ra gì?

---

# ĐÁP ÁN

1. `POSITIVE`
2. `NOT READY`
3. `NO POWER`
4. `START`
5. `DENY`
6. `NO CONFIG`
7. `run()` → `RUN`
8. `RUN`
9. `idle()` → `IDLE`
10. `wait()` → `WAIT`
