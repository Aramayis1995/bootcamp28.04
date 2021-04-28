# MY HOMEWARK 28.04

---

```javascript
let a = 10,
  b = 3;
a = a + b;
b = a - b;
a = a - b;
console.log(a);
console.log(b);
```

---

```javascript
let username = prompt("enter your username", "");
if (username === "admin") {
  let passward = prompt("enter your passward", "");
  if (passward === "TheMaster") {
    alert("Welcome!");
  } else if (passward !== "TheMaster" && passward !== "" && passward !== null) {
    alert("Wrong password");
  } else {
    alert("Canceled");
  }
} else if (username === "" || username === null) {
  alert("Canceled");
} else {
  alert("I don’t know you");
}
```

---
