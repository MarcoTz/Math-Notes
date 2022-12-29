Let $f:X\rightarrow Y$ be a finite morphism of nonsingular curves ([[Finite Morphisms of Schemes]],[[Curve (Scheme)]]), then a *local parameter* at a $Q\in Y$ is an element $t\in \mathcal{O}_Q$ with $v_Q(t)=1$ ([[Valuation Ring]])

Given a local parameter $t$ at $Q$, we define ([[Weil Divisor]])

$$ f^*:Div(Y)\rightarrow Div(X) \quad f^*Q = \sum_{f(P)=Q}v_P(t)P$$ This is well defined because $f$ is finite, and it is independent of the choice of $t$. 
$f^*$ preservers linear equivalence, so it induces a homomorphism $f^*:Cl(Y)\rightarrow Cl(X)$ .

For any divisor $D$ on $Y$, we have $deg(f^*D) = deg(f) deg(D)$ ([[Degree of a Morphism of Curves]]). Thus [[Principal Divisor]]s on complete nonsingular curves have degree $0$.