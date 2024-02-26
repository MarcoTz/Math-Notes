Given a [[Type System]] for a programming language, *subtyping* is a preorder ([[Order]] without antisymmetry) on types. 
It can be used to implement *subtype polymorphism*, that is reusing code for different types 
$$ (\lambda x: \{ y:Nat \}. \{ y = x.y+3\}) \{ z=3, y=5\} $$
(using [[Records]]).

Most subtyping systems have a type $\mathtt{Top}$ which is a supertype of every type, that is 

$$  \tau <: \mathtt{Top}$$ Sometimes they also have a bottom type, that is a subtype of every type 
$$ \mathtt{Bot} <: \tau$$ 
To ensure reflexivity and transitivity, they are also encoded as rules (although they can often be shown to be admissible)
$$ \tau <:\tau$$
$$ \frac{S<:U \quad U<:T}{S<:T}$$ 
A type system with subtyping also has a typing rule to allow subtypes for types:

$$ \frac{\Gamma \vdash t:\tau \quad \tau<:\sigma}{\Gamma \vdash t:\sigma}$$ 
This rule is often omitted or included in different rules to allow for decidable algorithms.


### Properties 

* A subtyping system is said to have *inversion* if the shape of types can be derived from subtyping rules that apply to it (e.g. if $S<: T_1\rightarrow T_2$ then $S=S_1\rightarrow S_2$ with $T_1<:S_1$ and $S_2<:T_2$.
* 
