#Haskell Notes 

## Lists
Lists are like group of arrays of same data type.
[[1,2],[2,4]]
## Tuples
Tuples are like group of arrays which can contain a mix type but group has to contain same number of elements such as 
[(1,2),(3,4),("E","D")]


## General Points
- Everything in Haskell has a type, so the compiler can reason quite a lot about your program before compiling it.
- A typeclass is a sort of interface that defines some behavior. If a type is a part of a typeclass, that means that it supports and implements the behavior the typeclass describes. A lot of people coming from OOP get confused by typeclasses because they think they are like classes in object oriented languages. Well, they're not. You can think of them kind of as Java interfaces, only better.