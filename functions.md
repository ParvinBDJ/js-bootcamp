# Functions

_Now we are going to talk about functions and what i have learned in het Javascript Bootcamp._

Functions are one of the most important thing in Javascript. They can be used to perform a set of statements or calculate
a sum. But before they do so you have to call the function so it knows when to perform its statements. 

During the bootcamp i went over the basics of functions and i  went deeper into functions. Its there i found out about 
higher-order functions. Higher-order functions are functions within a function. So you can call it a higher-order functions
when a functions accepts or returns a function. This was something which wasn't easy but after a while i got to understand
it better (which doesn't mean that i am 100% comfortable with them after the bootcamp). 

Common higher-order functions like: map, reduce & filter are the most used higher-order functions because by it as a higher-
order functions you don't have to write a loop. An example of such a functions is found below:

_const doorDeHelft= [10, 20, 30, 40];_

_const som = doorDeHelft.map(function(isDoorDeHelft){_

_return isDoorDeHelft / 2;_

_}_

_console.log(isDoorDeHelft);_

### Console:

_["Parvin", "Lola", "Jantje", "Niemand"]_
