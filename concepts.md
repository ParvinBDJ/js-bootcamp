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
