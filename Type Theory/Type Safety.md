In a typed language (that is with a way to assign types to terms), *type safety* roughly states that if a type can be assigned to a term, it will behave well.
It comes in two parts, *progress* and *preservation*.
Depending on the type system, these sometimes have to be stated differently.

### Progress

A well-typed term is never stuck, that is it is either a value, or it can be evaluated one step ([[Evaluation Orders in Lambda Calculus]])

### Preservation

If a well-typed term can be evaluated one step, then the resulting term is also well-typed.