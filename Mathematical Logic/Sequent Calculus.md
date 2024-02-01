Sequent Calculus is similar to [[Natural Deduction Systems]] using rules to prove assertions. Instead of having assertions, rules contain *sequents* of the form $\Gamma \Rightarrow C$, where $\Gamma$ is a multiset of formulas and $C$ is a single formula (or sometimes also a multiset, depending on the calculus). 
$\Gamma$ is called the *antecent* and $C$ the *succedent*.
The antecent can be thought of as assumptions and the succedent as the conclusions from these assumptions.

Additionally, there are some sequents, called *axioms* (similar to [[Axiomatic Logical Systems]]), which are assumed to be derivable.
Any other sequent is said to be *derivable*, if there is some derivation, that is consecutive application of rules in the calculus, starting with the sequent and ending in only axioms.

In a system of sequent calculus, a rule is called *admissable*, if any derivation of a sequent $\Gamma \Rightarrow C$ using this rule can be transformed into one without the rule.  

The *height* of a derivation is the maximal number of rules successively applied to reach the last sequent, denoted $\vdash _n \Gamma \Rightarrow C$, if $\Gamma \Rightarrow C$ can be derived with a derivation of height at most $n$.