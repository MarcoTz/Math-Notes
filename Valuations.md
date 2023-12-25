A *valuation* is a function from [[Propositional Formulas]] to $\{0,1\}$ (of true, false) that is arbitrary on atomic formulas and has the following properties 
* $v(\bot) = 0$
* $v(A\&B) = min(v(A),v(B))$
* $v(A\vee B) = max(v(A),v(B))$
* $v(A\supset B) = max(1-v(A),v(B))$

For sequents ([[Sequent Calculus]]) $\Gamma \Rightarrow \Delta$, valuations are extended by $v(\Gamma) = \bigwedge \Gamma$ and $v(\Delta) = \bigvee \Delta$ taking the conjunction or disjunction of all formulas.
## Refutability and Validity 

A sequent $\Gamma \Rightarrow \Delta$ is called *refuatable*, if there is some valuation $v$ such that $v(\Gamma) \leq v(\Delta)$. 
If a sequent is not refutable it is called valid.