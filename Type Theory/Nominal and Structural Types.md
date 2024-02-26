[[Type System]]s are generally split into two different kinds: *structural* and *nominal* type systems. These differ mainly in how [[Subtyping]] works.
Structural type systems define types based on their structures such as [[Records]] or [[Variant Types]]. These assign different types to terms with different structures. Subtyping is then based on the structures of these types (depth, widht for records, for example).
Nominal systems define types based on *names*, such as object oriented languages. 
Types are manually defined and any relationships between them are also defined by the programmer (such as subclasses in object oriented languages).