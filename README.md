# ios-development-notes

## Structs and Classes
Structs unlike in C Structs have methods

2 major differences
1. Structs have no inheritance.
2. Structs are value types and classes are reference types. Value types get copied. Arrays, Ints, Strings, Dictionaries are all Structs. Passing Structs arrown = copying them.

Other differenes
1. Structs get a free initializer which initializez all the variables. If you don't want the initializer to initialize everything you'll have to create your own.


## Type inference

var game: Concentratio = Concentration()

is the same as

var game = Concentration

Swift is a very strong typed language but it can figure out by it's own the type sometimes and can cast the object to its class.

## Internal and external names
Functions in Swift have a internal name and an external name:
 - internal name => used inside the method definition
 - external name => used when calling the method and passing arguements into it.
 
init can have the same internal and external name. Most of the other functions cannot but init is an exception.


## Property observers
lazy vars do not have property observers.
