A *fibration* is a map $p:E\rightarrow B$ between [[Topological Space]]s with the [[Homotopy Lifting Property]] wrt. all spaces $X$.

For a fibration $p:E\rightarrow B$, the fibers $F_b = p^{-1}(b)$ over each path-component ([[Path Connectedness]]) of $B$ are homotopy equivalent ([[Homotopy]]).

### Pullback fibration 

Given a fibration $p:E\rightarrow B$ and a map $f:A\rightarrow B$, the fibration $f^*(E) \rightarrow A$ with $f^*(E) = \{(a,e) \in A\times E | f(a) = p(e)\}$ s.t. the following diagram commutes ([[Diagram]]) is called the *pullback* or *induced* fibration.
![[Pullback fibration diagram.png]]

Given a fibration $p:E\rightarrow B$ and homotopy $f_t:A\rightarrow B$, the pullback fibrations $f^*_0(E) \rightarrow A$ and $f^*_1(E) \rightarrow A$ are homotopy equivalent ([[Homotopy]]).

Therefore, if $B$ is contractible, $p$ is homotopy equivalent to the projection $B\times F \rightarrow B$.

### Pathspace 

For $f:A\rightarrow B$, let $E_f = \{ (a,\gamma) | a\in A, \gamma : I \rightarrow B \text{ path } \gamma(0) = f(a)\}$, then $p:E_f \rightarrow B$, $p(a,\gamma) = \gamma (1)$ is a fibration.

### Prinicpal Fibration 

A fibration $F\rightarrow E \rightarrow B$ is called *principal* if there is a commutative diagram with the second row also a fibration and all verical maps weak homotopy equivalences
![[principal fibration diagram.png]]
