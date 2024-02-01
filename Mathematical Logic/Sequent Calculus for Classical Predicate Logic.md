This is the same system as [[Sequent Calculus for Classical Propositional Logic]], but with the following additional rules for [[Predicate Logic]]
![[G3c rules.png]]
These have additional restrictions. 
In $R\forall$, $y$ cannot occur free in $\Gamma,\Delta,\forall xA$ and in $L\exists$ $y$ cannot occur free in $\exists x A,\Gamma,\Delta$.
In this calculus, the rules of weakening, contraction and cut are all admissible.
All formulas in a derivation of $\Gamma \Rightarrow \Delta$ are subformulas of $\Gamma,\Delta$.
This system is consistent and complete.

### Substitution Lemma

If $\Gamma \Rightarrow \Delta$ is derivable and $t$ is free for $x$ in $\Gamma,\Delta$ then $\Gamma(t/x)\Rightarrow \Delta(t/x)$ is also derivable.