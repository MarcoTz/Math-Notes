
This is a system of natural deduction ([[Natural Deduction Systems]]) to infer [[Assertions]] using intuitionistic logic (that is without excluded middle $A \vee \sim A$).

It has the following rules:

![[Natural Deduction Introduction.png]]
![[Natural Deduction &E.png]]
![[Natural Deduction veeE.png]]
![[Natural Deduction supsetE.png]]
![[Natural Deduction falsumE.png]]

The rules marked with $I$ are called *introduction rules* while the ones marked with $E$ are called *elimination rules*.

Any time an introduction rule is used right before the corresponding elimination rule, the deviation can be simplified, removing those of these rules. This is called the *inversion principle*.

### Normal Form

We say a derivation in natural deduction is in *normal form* if all major premises (that is the ones with the connective that gets removed) of elimination rules are assumptions.

A system is said to have *normalization*, if there is a procedure to transform any derivation into one in normal form.
It is said to have *strong normalization* if this procedure terminates after a finite number of steps, regardless of the order in which the transformations were applied.
