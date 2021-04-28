# MY HOMEWARK 28.04

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
