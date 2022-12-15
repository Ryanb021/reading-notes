# Operators and Loops

[Source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
[Source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

table:

Name	                                     Shorthand operator	                Meaning
Assignment	                                x = f()	                           x = f()
Addition assignment	                        x += f()	                         x = x + f()
Subtraction assignment	                    x -= f()	                         x = x - f()
Multiplication assignment	                  x *= f()	                         x = x * f()
Division assignment	                        x /= f()	                         x = x / f()
Remainder assignment	                      x %= f()	                         x = x % f()
Exponentiation assignment	                  x **= f()	                          x = x ** f()
Left shift assignment	                      x <<= f()	                          x = x << f()
Right shift assignment	                    x >>= f()                          	x = x >> f()
Unsigned right shift assignment	            x >>>= f()	                        x = x >>> f()
Bitwise AND assignment	                    x &= f()	                          x = x & f()
Bitwise XOR assignment	                    x ^= f()	                          x = x ^ f()
Bitwise OR assignment                     	x |= f()	                          x = x | f()
Logical AND assignment	                    x &&= f()                         	x && (x = f())
Logical OR assignment                     	x ||= f()	                          x || (x = f())
Nullish coalescing assignment	              x ??= f()	                          x ?? (x = f())


Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}

There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

[Blog1](https://blog.hubspot.com/website/javascript-for-loops)
[Blog2](https://medium.com/geekculture/looping-vs-iteration-in-javascript-a-beginners-guide-to-navigating-both-571ecdfd9cfe)
[Blog3](https://www.edureka.co/blog/javascript-operators/)
