Let $R$ be a ring and $I\subseteq R$ an additive subgroup. Then

* $I$ is a *right ideal* if $xr\in I \quad \forall x\in I, r\in R$
* $I$ is a *left ideal* if $rx \in I \quad \forall x\in I, r\in R$
* $I$ is an *ideal* if it is both a right and left ideal

Clearly, $\{0\}$ and $R$ are ideals or $R$. They are called *trivial ideals*. All following definitions only use ideals, but they also work for left and right ideals by making appropriate replacements. 


#### Principal Ideal

An ideal $I$ of $R$ is called principal ideal, if there is an element $x\in I$ s.t. $I = RxR$. We say $I$ is *generated* by $x$.
If all ideals of $R$ are principal ideals, $R$ is called *principal ideal domain*.

#### Constructions of Ideals 

Given two ideals $I,J$ we have 

* $I+J = \{x+y | x\in I, y\in J\}$ is an ideal of $R$
* $I\cap J$ is an ideal or $R$
* $IJ = \{ \sum_i^n x_iy_i | n\in \mathbb{N}, x_i\in I, y_i\in J\}$ is an ideal of $R$ with $IJ\subseteq I\cap J$