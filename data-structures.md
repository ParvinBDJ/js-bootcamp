# Data structures
We are going to talk about how to structure your data in Javascript. For that there are a few structure things i am going to talk about. Which are: Arrays, Objects and Methods.

### Arrays
Arrays are ways that you can connect a set of values to a variable. You can for example use this if you want to store several numbers in a variable. You would do it like this:

```js
const arr = [1, 45, 64, 23, 53];
```
Now you have created a array with several numbers inside. Now say you want to put one number in the console. You would do it like this:
 
 ```js
const arr = [1, 45, 64, 23, 53];

console.log(arr[0]);
// 1
 ```
You migth be thinking: Why say: _arr[0]_ if you want to call the first number. That is because you start counting from 0 so 0 = 1 and 1 = 45.

### Objects
Objects are kind of similar to arrays. You can also store several values within it. But you write an object like _var : value_ look for the example below:
```js
const obj {
cijfer0: 1,
cijfer1: 45,
cijfer2: 64,
cijfer3: 23,
cijfer4: 53
};
```

If you would want to have the number 64 in the console you should write it like this;
```js
const obj {
cijfer0: 1,
cijfer1: 45,
cijfer2: 64,
cijfer3: 23,
cijfer4: 53
};

console.log(obj.cijfer2);
// 64
```
 

