# JavaScript Coding Guidelines

## Names
camelCase is used for ```function``` and ```method``` names
```js
function thisIsMyFunctionName() {...}
var fullName = "Test";
```

PascalCase is used for ```type``` names

Use concise names!

## Documentation
Use [JSDoc](https://jsdoc.app/about-getting-started.html) style comments when documenting code
```js
/** This function will display "Hello World" */
function showHelloWorld() {
    alert("Hello World");
}
```

## Curly Braces
For code blocks it is recommended to start the opening curly brace at the end of the
current line and put the closing brace on a separate line indented at the same level
as the starting block of code.
```js
if (true) {
    if (someCondition) {
        // Code here...
    }
    else if (something else) {
        // More code here...
    }
}
```
