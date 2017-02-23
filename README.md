JavaScript Intro to Functions Lab
---

## Objectives

1. Practice writing functions
2. Explain basics of working with strings
3. Explain the difference between `return` and logging
4. Practice using `return` and `console.log()`

## Introduction

Welcome to the JavaScript functions lab! You'll notice a few new things in this lesson that we haven't encountered before. Don't worry, we'll walk you through them.

Even if you've walked through some of this material before, it's a good idea to review as we code-along — we're writing functions now, after all.

In this lab, we're writing functions that "speak" at different volumes — they whisper or they shout. We're going to use what we learn practicing speaking in this way to write another function, `sayHiToGrandma()`, which takes our new-found speaking ability to greet our grandmother. She's not exactly deaf, but whispering can be a bit difficult. But she'll always hear you if you say, "I love you, Grandma."

Note that just like `.toUpperCase()` changes any string to all uppercase in JavaScript, `.toLowerCase()` (e.g., `'HELLO'.toLowerCase()`) changesany string to all lowercase.

Additionally, how do we check if a string is all lowercase or all uppercase?

```javascript
var uppercase = "HELLO!"

uppercase.toUpperCase() === uppercase // true

var lowercase = 'hello!'

lowercase.toLowerCase() === lowercase // true

var mixedCase = 'Hi there!'

mixedCase.toLowerCase() === mixedCase // false

mixedCase.toUpperCase() === mixedCase // false
```

We can simply check whether the string is the same when we convert it to uppercase or lowercase! If it's the same, then it was already in that case; if not, then it's either in the other case or it's mixed case.

