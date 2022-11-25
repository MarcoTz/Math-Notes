Let $f:X\rightarrow Y$ be a morhpism of [[Scheme]]s. The *diagonal morphism* is the unique morphism $\Delta : X\rightarrow X \times_Y X$ s.t. the compositions $p_1\circ \Delta$ and $p_2 \circ \Delta$ are the identity on $X$.
If the diagonal morphism is a closed immersion ([[Open and Closed Subschemes]]), $f$ is called *separated*. In this case we say $X$ is *separated over Y*.
A scheme is separated if it is separated over $Spec \mathbb{Z}$ 

A morphism between affine schemes is always separated.
An arbitrary morphism is separated iff the image of the diagonal morphism is a closed subset of $X\times_Y X$ .

### Valuative Criterion for Separatedness

Let $f:X\rightarrow Y$ be a morphism with $X$ a [[Noetherian Scheme]]. Then $f$ is separated iff the following condition holds. For any [[Field]] $K$ and [[Valuation Ring]] $R$ with [[Quotient Field]] $K$, let $T=Spec R$, $U=Spec K$ and $i:U\rightarrow T$ be the morphism induced by the inclusion $R\hookrightarrow K$. Given morphisms $T\rightarrow Y$ and  $U\rightarrow X$, commuting with $f$ and $i$, there is at most one morphism $T\rightarrow $X$ s.t. the following [[Diagram]] is commutative.
![[Separated Morphism Scheme.png]]