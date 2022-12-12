A [[Scheme]] $X$ is *locally noetherian*, if it can be covered by open affine subsets $SpecA_i$ ([[Spectrum]]) where each $A_i$ is a [[Noetherian Ring]].
$X$ is noetherian if it is locally noetherian and quasi-compact ([[Quasi-Compactness]]).
A scheme $X$ is locally noetherian iff for every open affine subset $U=SpecA$, $A$ is noetherian. In particular, an affine scheme $Spec A$ is noetherian iff $A$ is noetherian.

For a noetherian scheme we have the following properties
* Open and closed immersions are [[Separated Morphisms]] ([[Open and Closed Subschemes]])
* A composition of two separaed morphisms is separated
* If $f:X\rightarrow Y$ and $f^{\prime}:X^{\prime}\rightarrow Y^{\prime}$ are separated morphisms with $X$ and $Y$ schemes over $S$ ([[Scheme over a Scheme]]), then the product morphism $f\times f^{\prime} : X\times_S X^{\prime} \rightarrow Y\times_S Y^{\prime}$ is also separated
* if $f:X\rightarrow Y$ and $g:Y\rightarrow Z$ are two morphisms with $g\circ f$ separated, then $f$ is separated
* A morhpism $f:X\rightarrow Y$ is separated iff $Y$ can be covered by upen subsets $V_i$ s.t. $f^{-1}(V_i)\rightarrow V_i$ is separated for each $i$

* A closed immersion is a [[Proper Morphism]]
* A composition of proper morphisms is proper
* Proper morphisms are stable under [[Base Extension]]
* Products of proper morphisms are proper
* If $f:X\rightarrow Y$ and $g:Y\rightarrow Z$ are two morphisms with $g\circ f$ proper and $g$ separated, then $f$ is proper.
* Properness is local on the base as above