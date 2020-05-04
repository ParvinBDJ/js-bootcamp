# Concepts
### Binding and Scopes
Each binding is created within a scope. A binding created outside of a function or a block is made inside of the _global scope_. Which means anything can acces this. For example:
```js
var een = 1;

function niks(){
console.log(een);
// 1
}

console.log(een);
// 1
```

But when a binding is created within a function or block it made within the _local scope_, which means only the locals within the function can acces the value. For example:

```js
function niks(){
var een = 1;
console.log(een);
// 1
}

console.log(een);
// undefined
```

### Hoisting
Variable and function declarations are put on top of your code. This means that you can call a function before it is declared because Javascript buts the functions on top of your code. For example:

```js
niks();

function niks() {
var een = 1;
console.log(1);
}

```

You would expect this to be undefined but because of hoisting the function is found and the console will say:
```js
1
```

### Closures
A function is not only a function. It is also a closure, which means that it can take variables from outside of the function itself and use it. For example:
```js
const me = "Parvin";

function roepNaam(){
console.log("Hallo" + me);
}

roepNaam();
// Hallo Parvin
```
