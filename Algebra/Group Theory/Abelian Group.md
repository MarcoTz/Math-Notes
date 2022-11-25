A [[Group]] $G$ is called *abelian* if $\forall x,y\in G : xy=yx$ holds. We say the product is *commutative*. 
For an abelian group, we sometimes write $x+y$ for $xy$.


#### Cyclic Groups

A group $G$ is called *cyclic*, if there is an element $x\in G$ s.t. for each $y\in G$ there is a $n$ with $x^n=G$.  
Since $x^n x^m = x^n+m = x^mx^n$ any cyclic group is abelian.
We say $x$ *generates* $G$ and write $G = \langle x \rangle$ 
Each finite cyclic group with order $n$ is isomorphic to $\mathbb{Z}_n$ where $\mathbb{Z}_n = \mathbb{Z}/n\mathbb{Z}$ are the [[Integers]] mod $n$.

### Finitely Generated Abelian Groups

If an abelian group $G$ is finitely generated, there is a decomposition 

 $$ G \cong \mathbb{Z}^n \oplus \mathbb{Z}_{n_1} \oplus \dots \mathbb{Z}_{n_k}$$
 where $\oplus$ denotes the product ([[Group Products]]) of groups and $\mathbb{Z}_{n_i}$ is the finite cyclic group of order $n_i$.
 We say $n$ is the *rank* of $G$.
