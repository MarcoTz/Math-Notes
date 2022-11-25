A *$n$-simplex* is the convex hull ([[Convexity]]) of $n+1$ points $v_0,\dots,v_n$ in $\mathbb{R}^m$ ([[Euclidean Space]]) that do not lie in a hyperplane ([[Vector Space#Subspace]], [[Affine Space#Affine subspaces]]) of dimension less than $n$. We call the points $v_i$ the *vertices* and write $[v_0,\dots,v_n]$ for the simplex

The *standard $n$-simplex* is the following simplex: 

$$\Delta^n = [e_1,\dots,e_n,0] = \{(t_0,\dots,t_n)\in \mathbb{R}^n | \sum_{i}t_i=1, t_i\geq 0 \forall i\}$$
Sometimes we need and [[Order]] on the vertices of a simplex (especially [[Homology]]). In this case we say $v_i < v_j$ iff $i<j$ 

### Faces 

Given a $n$-simplex $[v_0,\dots,v_n]$, if we remove a vertex $v_i$, we get a $n-1$-simplex, denoted by $[v_0,\dots,\hat{v_i},\dots,v_n]$. These simplices are called *faces* of $[v_0,\dots,v_n]$.
The union of all faces of $[v_0,\dots,v_n]$ is called the *boundary* of $[v_0,\dots,v_n]$, denoted $\partial[v_0,\dots,v_n]$.
The *open simplex* is $[v_0,\dots,v_n]\setminus \partial [v_0,\dots,v_n]$. For $\Delta^n$ we denote this by $\mathring{\Delta}^n$.

### Barycentric coordinates

Given any $n$-simplex $[v_0,\dots,v_n]$, there is a canonical linear homeomorphism ([[Linear Map]],[[Continous Function#Homeomorhpism]]) $[v_0,\dots,v_n]\rightarrow \Delta^n$, given by $(t_0,\dots,t_n)\mapsto \sum_i t_i v_i$.
This homeomorphism preserves the order of vertices, and the coefficients $t_i$ are called *barycentric coordinates* of the point in $\Delta^n$.