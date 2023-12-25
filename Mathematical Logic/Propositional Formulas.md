In propositional logic, formulas have the form 
1. Prime formulas $P,Q,\dots$, also called *atomic* formulas and $\bot$, the *falsum*
2. For formulas $A$ and $B$, the *conjuction* $A\& B$ is a formula
3. For formulas $A$ and $B$, the *disjunction* $A\vee B$ is a formula 
4. For formulas $A$ and $B$, *implication* $A \supset B$ is a formula

Implication is also often written as $A\rightarrow B$ or $A\Rightarrow B$.
The formula $\sim A = A \supset \bot$ is called the *negation* of $A$ and $A\supset \subset B$ is called *equivalence* of $A$ and $B$.
When no brackets are used, we assume $\vee$ and $\&$ are stronger binding than $\supset$, that is $A\supset B \vee C$ is the same as $A \supset (B\vee C)$.

Depending on the derivation rules used, some of these can be defined in terms of others and other base formulas can be used. For example, in classical propositional logic, $\sim$ and $\&$ are enough to define all others.

The *weight* of a formula is defined as 
* $w(\bot) =0$
* $w(P) =1$ for atoms $P$
* $w(A\circ B) = w(A)+w(B)+1$ for $\circ = \&,\vee,\supset$