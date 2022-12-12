Let $S$ be a [[Scheme]] and $X,Y$ be schemes over $S$ ([[Scheme over a Scheme]]). Then the *fibred product of $X$ and $Y$ over $S$*, denoted $X\times_S Y$ is a scheme with morphisms $p_1:X\times_S Y \rightarrow X$ and $p_2: X\times_S Y \rightarrow Y$, called *projection morphisms* which make a commutative [[Diagram]] with the given morphisms to $S$ and satisfy the following universal property. 
Given any other scheme $Z$ over $S$ and morphisms $f:Z\rightarrow X$, $g:Z\rightarrow Y$, which commute with the given morphisms to $S$, there is a unique morphism $\theta:Z\rightarrow X\times_S Y$ s.t. $f = p_1\circ \theta$ and $g = p_2 \circ \theta$

![[Fibred Product Diagram.png]]

If $X$ and $Y$ are any two morphims, we take $S=Spec\mathbb{Z}$ and define the *product* $X\times Y = X\times _{Spec\mathbb{Z}} Y$. 

The fibre product exists for any schemes $X,Y,S$ and is unique up to isomorphism.