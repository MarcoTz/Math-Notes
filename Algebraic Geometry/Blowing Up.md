Let $X$ be a [[Noetherian Scheme]] and $\mathcal{I}$ a coherent sheaf of ideals ([[Sheaf of Ideals]]) on $X$. Then let $\mathcal{J} = \bigoplus_{d\geq 0}\mathcal{J}^d$ the sheaf of graded $\mathcal{O}_X$-algebras ([[Graded Ring]]), where $\mathcal{J}^d$ is the $dth$ power of $\mathcal{J}$ with $\mathcal{J}^0=\mathcal{O}_X$. Then $X,\mathcal{J}$ satisfy the conditions of [[Proj]] and we can define $\tilde{X}=Proj\mathcal{J}$. We call $\tilde{X}$ the *blowing-up* of $X$ wrt $\mathcal{I}$. If $Y$ is the closed subscheme of $X$ corresponding to $\mathcal{I}$, we call $\tilde{X}$ the *blowing-up* of $X$ along $Y$ or with center $Y$.

The Blowing up has the following properties:

* the [[Inverse Image Ideal Sheaf]] $\tilde{\mathcal{I}} = \pi^{-1}\mathcal{I}\cdot \mathcal{O}_{\tilde{X}}$ is an invertible sheaf ([[Free Scheaf of Modules]])
* If $Y$ is the closed subscheme corresponding to $\mathcal{I}$, then $\pi: \pi^{-1}(X\setminus Y)\rightarrow X\setminus Y$ is an isomorphism

If $X$ is a [[Variety]] ([[Schemes and Varieties]]) over an algebraically closed [[Field]] $k$, $\mathcal{I}\subseteq \mathcal{O}_X$ a nonzero coherent sheaf of ideals on $X$ and $\pi:\tilde{X}\rightarrow X$ the blowing up wrt. $\mathcal{I}$, then
* $\tilde{X}$ is a variety
* $\pi$ is birational, proper and surjective ([[Birational Map]],[[Proper Morphism]])
* if $X$ is (quasi-)projective ([[Projective Scheme]]) then so is $\tilde{X}$ and $\pi$ is a [[Projective Morphism]]

Let $X$ be a nonsingular ([[Singularities]]) variety over a field $k$ the $Y\subseteq X$ a nonsingular closed subvariety with ideal sheaf $\mathcal{I}$. Let $\pi:\tilde{X}\rightarrow X$ be the blowing up of $\mathcal{I}$ and $Y^{\prime}\subseteq \tilde{X}$ the subscheme defined by the [[Inverse Image Ideal Sheaf]] $\mathcal{I}^{\prime} = \pi^{-1}\mathcal{I}\cdot \mathcal{O}_{\tilde{X}}$. Then
* $\tilde{X}$ is also nonsingular
* $Y^{\prime}$ with the induced projection map $\pi:Y^{\prime} \rightarrow Y$ is isomorphic to $\mathbb{P}(\mathcal{I}/\mathcal{I}^2)$ on the projective space bundle ([[Projective Sheaf Bundle]]) associated to the (locally free) sheaf $\mathcal{I}/\mathcal{I}^2$ on $Y$
* under this isomorphism, the normal sheaf ([[Normal and Conormal Sheaf]]) $\mathcal{N}_{Y^{\prime}/\tilde{X}}$ corresponds to $\mathcal{O}_{\mathbb{P}(\mathcal{I}/\mathcal{I}^2)}(-1)$  

### Universal Property of blowing up

Let $X$ be a noetherian scheme, $\mathcal{I}$ a coherent sheaf of ideals and $\pi:\tilde{X}\rightarrow X$ the blowing up of $X$ wrt $\mathcal{I}$. Then for any morphism $f:Z\rightarrow X$ s.t. $f^{-1}\mathcal{I}\cdot \mathcal{O}_Z$ is an invertible sheaf of ideals on $Z$, there exists a unique morphism $g:Z\rightarrow \tilde{X}$ s.t. the following diagram commutes ([[Diagram]])

![[Blowing Up.png]]

### Blowing up and Birational Morphisms

If $X$ is a quasi-projective variety over an algebraically closed field $k$, $Z$ another variety and $f:Z\rightarrow X$ a birational projective morphism, then there exists a coherent sheaf of ideals $\mathcal{I}$ on $X$ s.t. $Z$ is isomorphic to the blowing up $\tilde{X}$ of $X$ wrt $\mathcal{I}$ and $f$ corresponds to $\pi:\tilde{X}\rightarrow X$ under this isomorphism.