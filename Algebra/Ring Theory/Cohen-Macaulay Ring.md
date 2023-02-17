
Let $A$ be a local noetherian ring ([[Local Ring]],[[Noetherian Ring]]). Then if $depthA=dimA$ ([[Regular Sequence]]), $A$ is called *Cohen-Macaulay*.

For a local noetherian ring $A$ with maximal ideal $m$, we have 

* If $A$ is regular, it is Cohen-Macaulay
* If $A$ is Cohen-Macaulay, any [[Localization]] of $A$ at a [[Prime Ideal]] is Cohen-Macaulay
* If $A$ is Cohen-Macaulay and $x_1,\dots,x_r\in m$. Then $x_1,\dots,x_r$ form a regular sequence for $A$ iff $dimA/(x_1,\dots,x_r)= dim A - r$ 
* If $A$ is Cohen-Macaulay and $x_1,\dots,x_r\in m$ is a regular sequence for $A$, then $A/(x_1,\dots,x_r)$ is also Cohen-Macaulay
* If $A$ is Cohen-Macaulay and $x_1,\dots,x_r\in m$ is a regular sequence, let $I=(x_1,\dots,x_r)$. Then the natural map $(A/I)[t_1,\dots,t_r]\rightarrow gr_IA = \bigoplus_{n\geq 0} I^n/I^{n+1}$ defined by $t_i\mapsto x_i$ is an isomorphism, i.e. $I/I^2$ is a free $A/I$-[[Module]] of rank $r$ and for each $n\geq 1$ the natural map $S^n(I/I^2)\rightarrow I^n/I^{n+1}$ is an isomorphism (where $S^n$ denotes the symmetric power ([[Tensor Operations on Modules]]))