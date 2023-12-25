This is a system of [[Sequent Calculus]] for classical propositional logic instead of intuitionistic propositional logic (as [[Sequent Calculus for Intuitionistic Propositional Logic]]).
It only differs from this system by the addition of excluded middle, that is $\Rightarrow A \vee \sim A$ is always derivable. 
This is done by allowing the succedent of a sequent to be a multiset as well, instead of only a single formula, and making all rules symmetric.

This system has the following rules

![[Rules G3cp.png]]

The following rules are all admissible in the calculus
![[Structural Rules G3p.png]]
![[Cut G3c.png]]
### Trace Formula

Any sequent $\Gamma \Rightarrow \Delta$ can be transformed into topsequents of the form 
$$\bot,\dots,\bot, P_1,\dots,P_m \Rightarrow Q_1,\dots,Q_n,\bot,\dots,\bot$$
by successively applying the above rules.
This decomposition is unique.

A *regular sequent* is a sequent of the form $P_1,\dots,P_m \Rightarrow Q_1,\dots,Q_n,\bot,\dots,\bot$ with $P_i\neq Q_j$ for all $i,j$. 
After transforming a sequent into topsequent form, and removing all topsequents with $\bot$ on the left (these are conclusions of $L\bot$), we only have normal form sequents left.

The *trace formula* of a regular sequent $P_1,\dots,P_m \Rightarrow Q_1,\dots, Q_n,\bot,\dots,\bot$ is defined as 
* $P_1\&\dots\&P_m \supset Q_1 \vee \dots\vee Q_n$ if $m,n>0$
* $Q_1\vee\dots\vee Q_m$ if $m=0,n>0$
* $\sim(P_1\&\dots\&P_m)$ for $m>0,n=0$
* $\bot$ for $m,n=0$.

Then any formula $C$ is equivalent to the conjunction of all trace formulas of its regular sequents.

### Soundness and Completeness

*Soundness*: A sequent $\Gamma\Rightarrow \Delta$ derivable in this calculus is valid ([[Valuations#Refutability and Validity]]) 
*Completeness*: If a sequent $\Gamma \Rightarrow \Delta$ is valid, it is derivable.