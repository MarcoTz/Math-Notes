A *category* $\mathcal{C}$ consists of the following

1. A collection (not [[Sets]]) of *objects* $Ob(\mathcal{C})$
2. For any two objects $X,Y\in Ob(\mathcal{C})$ a collection of *morhpisms* $Mor(X,Y)$ 
3. A composition mapping (not a [[Function]]) $\circ : M(X,Y)\times M(Y,Z) \rightarrow M(X,Z)$ for any $X,Y,Z\in Ob(\mathcal{C})$

satisfying the following axioms:

1. For any $X\in Ob(\mathcal{C})$ there is an *identity morphism* $\mathbb{1}_X\in Mor(X,X)$ 
2. For any $f\in Mor(X,Y)$ we have $f\circ \mathbb{1}_Y = f$ and $\mathbb{1}_X\circ f  = f$ 
3. For any three morphisms $f\in Mor(X,Y)$, $g\in Mor(Y,Z)$ and $h\in Mor(Z,W)$ we have $f\circ(g\circ h) = (f\circ g)\circ h$ 