A *category* $\mathcal{C}$ consists of the following

1. A collection (not [[Sets]]) of *objects* $Ob(\mathcal{C})$
2. For any two objects $X,Y\in Ob(\mathcal{C})$ a collection of *morhpisms* $Mor(X,Y)$ 
3. A composition mapping (not a [[Function]]) $\circ : M(X,Y)\times M(Y,Z) \rightarrow M(X,Z)$ for any $X,Y,Z\in Ob(\mathcal{C})$

satisfying the following axioms:

1. For any $X\in Ob(\mathcal{C})$ there is an *identity morphism* $\mathbb{1}_X\in Mor(X,X)$ 
2. For any $f\in Mor(X,Y)$ we have $f\circ \mathbb{1}_Y = f$ and $\mathbb{1}_X\circ f  = f$ 
3. For any three morphisms $f\in Mor(X,Y)$, $g\in Mor(Y,Z)$ and $h\in Mor(Z,W)$ we have $f\circ(g\circ h) = (f\circ g)\circ h$ 

A map $f \in Mor(X,Y)$ is called an *isomorphism* if there is some $g\in Mor(Y,X)$ with $f\circ g = \mathbb{1}_Y$ and $g\circ f = \mathbb{1}_X$. In this case we say $X$ and $Y$ are *isomorphic*. 

### Product Category 

For categories $\mathcal{A}$ and $\mathcal{B}$, the *product category* $\mathcal{A}\times \mathcal{B}$ of $\mathcal{A}$ and $\mathcal{B}$ is the category with objects $(A,B)$ for $A\in\mathcal{A}$ and $B\in\mathcal{B}$ and morphisms $(f,g)\in Mor((A,B),(A^{\prime},B^{\prime}))$ whenever $f\in Mor(A,A^{\prime})$ and $g\in Mor(B,B^{\prime})$.

### Subcategory 

For a category $\mathcal{A}$, a *subcategory* $\mathcal{I}$ of $\mathcal{A}$ is a subcollection of objects of $\mathcal{A}$ along with a subcollection of $Mor(A,A^{\prime})$ for all $A,A^{\prime}\in \mathcal{I}$ satisfying the category axioms.
A subcategory $\mathcal{I}$ is called *full*, if for each $A,A^{\prime}$ the morphism collections $Mor(A,A^{\prime})$ in $\mathcal{I}$ and $\mathcal{A}$ are equal (that is $\mathcal{I}$ contains all possible maps).