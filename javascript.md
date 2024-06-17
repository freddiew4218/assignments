### Task 1: Sum All Salaries
```javascript
let salaries = {
    John: 100,
    Ann: 160,
    Pete: 130
};

let sum = 0;
for (let key in salaries) {
    sum += salaries[key];
}

console.log(sum); // Output should be 390
```

### Task 2: Multiply Numeric Properties
```javascript
function multiplyNumeric(obj) {
    for (let key in obj) {
        if (typeof obj[key] === 'number') {
            obj[key] *= 2;
        }
    }
}

let menu = {
    width: 200,
    height: 300,
    title: "My menu"
};

multiplyNumeric(menu);
console.log(menu); 
// Output should be:
// { width: 400, height: 600, title: "My menu" }
```

### Task 3: Check Email ID
```javascript
function checkEmailId(str) {
    let atIndex = str.indexOf('@');
    let dotIndex = str.indexOf('.');
    
    if (atIndex > 0 && dotIndex > atIndex + 1) {
        return true;
    } else {
        return false;
    }
}

console.log(checkEmailId("test@example.com")); // true
console.log(checkEmailId("test.example@com")); // false
console.log(checkEmailId("testexample.com"));  // false
console.log(checkEmailId("test@examplecom"));  // false
```

### Task 4: Truncate String
```javascript
function truncate(str, maxlength) {
    if (str.length > maxlength) {
        return str.slice(0, maxlength - 3) + "...";
    } else {
        return str;
    }
}

console.log(truncate("What I'd like to tell on this topic is:", 20)); // "What I'd like to te..."
console.log(truncate("Hi everyone!", 20));                          // "Hi everyone!"
```

### Task 5: Array Operations
```javascript
// Create an array styles with items “James” and “Brennie”.
let styles = ["James", "Brennie"];
console.log(styles); // ["James", "Brennie"]

// Append “Robert” to the end.
styles.push("Robert");
console.log(styles); // ["James", "Brennie", "Robert"]

// Replace the value in the middle by “Calvin”.
let middleIndex = Math.floor(styles.length / 2);
styles[middleIndex] = "Calvin";
console.log(styles); // ["James", "Calvin", "Robert"]

// Remove the first value of the array and show it.
let removedFirst = styles.shift();
console.log(removedFirst); // "James"
console.log(styles);       // ["Calvin", "Robert"]

// Prepend Rose and Regal to the array.
styles.unshift("Rose", "Regal");
console.log(styles);       // ["Rose", "Regal", "Calvin", "Robert"]
```
