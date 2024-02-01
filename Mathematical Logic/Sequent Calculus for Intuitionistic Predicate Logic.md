This is the same as [[Sequent Calculus for Intuitionistic Propositional Logic]], but with the following additional rules for [[Predicate Logic]].
![[G3i rules.png]]
For these rules, there are some additional restrictions. in $R\forall$, $y$ cannot be free in $\Gamma$, $\forall x A$, and in $L\exists$, $y$ cannot be free in $\exists x A, \Gamma, C$.
In this calculus, the rules of contraction, weakening and cut are all admissible.
All formulas in a derivation $\Gamma \Rightarrow C$ are subformulas of $\Gamma,C$.
This system is consistent.

The following sequents are not derivable in this system
* $\Rightarrow \forall x (A\vee B) \supset (A\vee \forall x B$
* $\Rightarrow (A\supset \exists x B) \supset \exists x( A\supset B)$
* $\Rightarrow (\forall x B \supset A) \supset \exists x (B\supset A)$ 
### Substitution Lemma

If $\Gamma\Rightarrow C$ is derivable and $t$ is free for $x$ in $\Gamma,C$, then $\Gamma (t/x) \Rightarrow C(t/x)$ is derivable