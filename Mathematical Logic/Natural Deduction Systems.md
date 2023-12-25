Given a formula $A$, a system of *natural deduction* has rules of inference, to infer [[Assertions]] from given *assumptions*, which are the only ones that are given at the start of inference (similar to axioms in [[Axiomatic Logical Systems]]).

The rules of inference have the form
$$ \frac{\vdash A \quad \vdash B}{\vdash A \& B}$$

Sometimes, rules may have an assumption that will be *discharged*, that is will be removed from the assumptions with this rule. In this case, the assumption is written as $[\vdash A]$.