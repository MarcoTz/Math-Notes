Given a programming language, a type system is a way to assign *types* $\tau$ to terms $t$ of the language.
There is a fixed set of types in a type system, consisting of [[Base Types]] such as Integers or Strings and *Type Constructors* such as function types, that create new types from given types (such as the function type $\tau_1\rightarrow \tau_2$ ([[Simply Typed Lambda Calculus]]). 

Assigning a term $t$ a type $\tau$ is usually written $t:\tau$ and when there is an *environment* $\Gamma$ containing additional information needed to assign types, we write $\Gamma \vdash t:\tau$. Such environments usually contain types for variables in the language.

### Properties 

* A type system is said to have *inversion* if the shape of a term can be derived from the typing rule that applies to it (e.g. if $t:S_1\rightarrow S_2$ then $t=\lambda x:S_1.t_2$ with $t_2:S_2$.
* A type system is said to be *invariant under substitution* if whenever $\Gamma \vdash t:\tau$ then $\Gamma \vdash t[t_2/x]:\tau$ if $\Gamma \vdash t_2:\tau^{\prime}$ when $x:\tau^{\prime}\in\Gamma$.   
* A type system is said to have *canonical forms*, if for any value *v* of type $\tau$, the shape of $v$ can be inferred (e.g. if $v:\tau_1\rightarrow \tau_2$ then $v=\lambda x:\tau_1,t$)