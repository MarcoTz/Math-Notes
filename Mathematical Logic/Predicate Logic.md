
Formulas in *Predicate Logic* are generalizations of [[Propositional Formulas]], defined as follows.
*Terms* are
* Constants $a,b,\dots$
* Variables $x,y,\dots$
* Applications of a $n$-ary function $f^n$ to terms $t_1,\dots,t_n$, $f^n(t_1,\dots,t_n)$

*Formulas* are 
* $\bot$ 
* Application of an $n$-ary predicate $P^n$ to $n$ terms $t_1,\dots,t_n$ $P^n(t_1,\dots,t_n)$.
* For any two formulas $A$ and $B$, $A\& B$, $A\vee B$ and $A\supset B$ 
* For any formula $A$, $\forall x A$ and $\exists x A$

Weight for a predicate formula is defined as for propositional formula with the additional definitions
* $w(\forall xA) = w(A)+1$
* $w(\exists x A) = w(A)+1$

For predicate formulas, [[Valuations]] are extended with the following rules 
* $v(\forall xA) = inf(v(A(x_i/x))$ 
* $v(\exists x A) = sup(v(A(x_i/x))$ 

### Free Variables 

For a term $t$, the *free variables* in $t$ are 
* $FV(a) = \emptyset$ for a constant $a$
* $FV(x) = \{x\}$ for a variable $x$
* $FV(f^n(t_1,\dots,t_n)) = FV(t_1)\cup\dots FV(t_n)$ 
For a formula $A$, free variables in $A$ are 
* $FV(\bot) = \emptyset$ 
* $FV(P^n(t_1,\dots,t_n)) = FV(t_1) \cup \dots \cup FV(t_n)$ 
* $FV(A\& B) = FV(A\vee B) = FV(A\supset B)=FV(A) \cup FV(B)$
* $FV(\forall x A) = FV(\exists x A) = FV(A)\setminus \{x\}$ 
If $FV(t) = \emptyset$, $t$ is called *open*, otherwise it is called *closed*. In $\forall x A$ and $\exists x A$, $x$ is called a *bound variable*.


### $\alpha$-conversion

We always assume that $\forall x A$ and $\forall y B$ if $A$ and $B$ are equal, except that in $B$, whenever $x$ appears in $A$, $y$ appears in $B$ instead. 
The same is true for $\exists x A$.
Renaming a bound variable in a formula $\forall xA$ to a different one, is called *$\alpha$-conversion*.

### Substitution

Replacing a variable $x$ by a term $t$ is called *subtitution* of $t$ for $x$, written $[t/x]$, and for a term or formula $A$, we write $A(t/x)$ for the result of performing $[t/x]$ in $A$. 
Subsitution is defined as follows 
* *a(t/x) = a* for a constant $a$
* $y(t/x) = y$ for $y\neq x$ and $y(t/x) = t$ if $x=y$ for a variable $y$.
* $f^n(t_1,\dots,t_n)(t/x) = f^n(t_1(t/x),\dots,t_n(t/x))$ 
* $\bot(t/x) =\bot$
* $(P^n(t_1,\dots,t_n))(t/x) = P^n(t_1(t/x),\dots,t_n(t/x))$ 
* $(A\circ B)(t/x) = A(t/x) \circ B(t/x)$ for $\circ = \&,\vee,\supset$
* $(\forall y A)(t/x) = \forall y A(t/x)$ if $y\neq x$, $(\forall y A)(t/x) = \forall y A$ if $y=x$
* $(\exists y A)(t/x) = \exists y A(t/x)$ if $y\neq x$, $(\exists y A)(t/x) = \exists y A$ if $y=x$.
A term $t$ is called *free for $x$ in $A$*, if in $A(t/x)$ no free variable of $t$ becomes bound.