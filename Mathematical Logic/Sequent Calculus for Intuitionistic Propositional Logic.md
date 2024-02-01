This is a [[Sequent Calculus]] system to describe intuitionistic logic using [[Propositional Formulas]]. It contains the following rules: 
![[Intuitionistic Sequent Calculus.png]]

In this system, the following rules of *weakening*, *contraction* and *cut* are all admissible
![[G3ip admissible.png]]

For any derivation of $\Gamma \Rightarrow C$ in this calculus, any formulas appearing in any rules, are subformulas of $\Gamma$ or $C$.
The derivability of any formula in this system is *decidable*.
### Inversion Lemma

In this calculus we have the following 
* If $\vdash _n A\& B, \Gamma \Rightarrow C$, then $\vdash_n A,B,\Gamma \Rightarrow C$ 
* If $\vdash _n A\vee B, \Gamma \Rightarrow C$, then $\vdash_n A,\Gamma \Rightarrow C$ and $\vdash_n B,\Gamma \Rightarrow C$ 
* If $\vdash _n A \supset B, \Gamma \Rightarrow C$, then $\vdash _n B,\Gamma \Rightarrow C$

### Underivable Formulas 

The following sequents are not derivable in this calculus
 * $\Rightarrow P \vee \sim P$ 
 * $\Rightarrow \sim P \vee \sim \sim P$
 * $\Rightarrow (( P \supset Q)\supset P) \supset P$ 
 * $\Rightarrow (P\supset Q \vee R) \supset (P\supset Q)\vee (P\supset R)$