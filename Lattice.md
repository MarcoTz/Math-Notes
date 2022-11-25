A *Lattice* $L$ in $\mathbb{R}^n$ is a set of points in $\mathbb{R}^n$ with the following properties 
1. For any two $x,y\in L$, we have $x+y,x-y\in L$ 
2. There is some $\varepsilon >0$, s.t. $||x-y||>\varepsilon$ $\forall x,t\in L$
3. There is some $\epsilon >0$ s.t. for each $x\in L$ there is some $y\in L$ with $||x-y||<\epsilon$ 

With these axioms, a lattice has to be a  subgroup ([[Group#Subgroups]]) of the additive group of $\mathbb{R}^n$ ([[Vector Space]]), and thus must be contained in some $d$-dim subspace of $\mathbb{R}^n$. 
The maximum $d$ such that this holds, is called the *dimension* of $L$.

If we pick $d$ linearly independent points of $L$, then any other point in $L$ is a linear combination of these points, so we say they form a *basis* of $L$. 
Furthermore, we can see that $L$ is a finitely generated free abelian group ([[Free Groups]]), so it is isomorphic to $\mathbb{Z}^n$.