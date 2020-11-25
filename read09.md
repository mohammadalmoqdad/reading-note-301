# Functional programming :
  - s a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
#### What makes a function pure?
  - It returns the same result if given the same arguments
  - It does not cause any observable side effects.
  - Any function that relies on a random number generator cannot be pure.
## Immutability:
  - Unchanging over time or unable to be changed.
  - When data is immutable, its state cannot change after it’s created.
  - If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

* ***pure functions + immutable data = referential transparency***
### Functions as first-class entities can:
  - refer to it from constants and variables.
  - pass it as a parameter to other functions.
  - return it as result from other functions.
#### Higher-order functions:
  - takes one or more functions as arguments, or
  - returns a function as its result.
  - **Filter**:the filter function expects a true or false 