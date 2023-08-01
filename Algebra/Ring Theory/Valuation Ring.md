For a field $K$ and a totally ordered ([[Order]]) [[Abelian Group]] $G$, a *valuation* of $K$ with values in $G$ is a map $\nu:K\setminus\{0\}\rightarrow G$ s.t. for $x,y\in K^*$ we have 

* $\nu(xy)=\nu(x)+\nu(y)$
* $\nu(x+y) \geq min(\nu(x),\nu(y))$
If $\nu$ is a valuation, $R=\{x\in K|\nu(x)\geq 0\}\cup \{0\}$ is a sub[[ring]] of $K$, called *valuation ring of $\nu$*. Then $m=\{x\in K|\nu(x)>0\}\cup \{0\}$ is an [[Ideal]] in $R$ and $(R,m)$ is a [[Local Ring]].

A valuation ring is an [[Integral Domain]] and is the valuation ring of some valuation of its [[Quotient Ring]].

### Discrete Valuation Rings

A valuation $\nu$ is called *discrete* if its value group $G$ is the [[Integers]]. The corresponding valuation ring is called *discrete valuation ring*.

If $R$ is a DVR with valuation $\nu:K^*\rightarrow \mathbb{Z}$ then 
* $x\in R$ is invertible iff $\nu(x) = 0$ 
* $R$ is local ([[Local Ring]]) with maximal ideal $m = \{ x\in R | \nu(x) > 0\} \cup \{0\}$ 
* $R$ is normal ([[Normal Ring]])
* $R$ is a principal ideal domain ([[Ideal#Principal Ideal]])
* $R$ is noetherian ([[Noetherian Ring]])
* The only nontrivial prime ideal ([[Prime Ideal]]) of $R$ is $m$