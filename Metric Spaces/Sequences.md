A *sequence* in a [[Metric Space]] $X$, is a family of elements $\{a_n\})_{n \in\mathbb{N}}$ indexed by [[Natural numbers]].

### Convergence 

A sequence $a_n$ is said to *converge* to an element $a\in X$, if for each $\varepsilon \geq 0$ there is a $n_0\in\mathbb{N}$ with $d(a_n,a)<\varepsilon$ for each $n>n_0$.

### Cauchy Sequences
A sequence $a_n$ is called a *Cauchy sequence* if for each $\varepsilon >0$, there is a $n_0\in \mathbb{N}$ s.t. $d(a_n,a_m)<\varepsilon$ for all $n,m>n_0$.
Every convergent sequence is a Cauchy sequence.

### Completeness

A metric space $X$ is called *complete* if every Cauchy sequence is convergent. 
For every metric space $X$, there is a metric space $\bar{X}$, containing $X$ that is complete.
The smallest such space (ordered by inclusion) is called the *completion* of $X$
