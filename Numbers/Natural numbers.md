The set ([[Sets]]) of *Natural Numbers*, written $\mathbb{N}$ is the set containing all numbers $0,1,2,\dots$. Sometimes $0$ is excluded from this definition.
In Zermelo-Fraenkel Set Theory, they are usually defined the following way: $0=\emptyset$ and $n+1 = n \cup \{n\}$, so we get $1 = \{ 0,\{0\}\}$, $2=\{1,\{1\}\}$ and so on.

The natural numbers (with $0$) and $+$ define a [[Monoid]]

### Peano Axioms

The natural numbers can also be defined using the *Peano Axioms*, which do not require a set-theoretic definition

1. $0$ is a natural number (i.e. $0$ exists). If $0$ is excluded we can also replace $0$ with $1$ in all axioms
2. Every natural number has a successor, which is also a natural number ($n+1=n\cup\{n\}$ in ZFC)
3. $0$ is not the successor of any natural number
4. If the successor of $x$ is the successor of $y$ then $x=y$
5. *The Axiom of Induction*: If a statement is true for $0$, and the statement being true for $x$ implies the statement being true for the successor of $x$, then the statement is true for all natural numbers

### Countable Sets

The cardinaltity of $\mathbb{N}$ is called *countable infinity*. Any set with the same cardinality is also called *countably infinite*. This can be shown using a bijection ([[Function#Injections Surjections and Bijections]]) between $\mathbb{N}$ and the set in question. 
Not all infinite sets are countable, for example the power set ([[Sets#Zermelo-Fraenkel Set Theory]]) of $\mathbb{N}$ is not countable.
