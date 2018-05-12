# ios-development-notes

## Structs and Classes
Structs unlike in C Structs have methods

2 major differences
1. Structs have no inheritance.
2. Structs are value types and classes are reference types. Value types get copied. Arrays, Ints, Strings, Dictionaries are all Structs.

Other differenes
1. Structs get a free initializer which initializez all the variables.


## Type inference

var game: Concentratio = Concentration()

is the same as

var game = Concentration

Swift is a very strong typed language but it can figure out by it's own the type sometimes and can cast the object to its class.
