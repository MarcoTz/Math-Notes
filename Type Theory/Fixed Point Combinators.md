In systems like [[Untyped Lambda Calculus]], recursion can immediately implemented, for example with the *$Y$-combinator* 
$$ Y = \lambda f. (\lambda x. f\ (x\ x))(\lambda x.f\ (x\ x))$$ However in a safe [[Type System]] ([[Type Safety]]), such a combinator can never be well-typed, so recusion needs to be explicitly included in the system.
This can be done with a term $\mathtt{fix}\ t$ , which is typed with the rule 
$$ \frac{\Gamma \vdash t_1:\tau_1}{\Gamma \vdash\mathtt{fix}\ x:\tau_1}$$
Evaluation ([[Evaluation Relation]]) of fixed points are then done with the rules

$$ \mathtt{fix}(\lambda x:\tau_1.t_2) \mapsto t_2[(\lambda x:\tau_1.t_2)/x]$$ 
$$\frac{t_1\mapsto t_1^{\prime}}{\mathtt{fix}\ t_1 \mapsto \mathtt{fix}\ t_1^{\prime}}$$
For easier syntax, $\mathtt{fix}$ can be used to define the [[Derived Form]] $\mathtt{letrec}$

$$ \mathtt{letrec}\ x:\tau_1=t_1\ \mathtt{in}\ t_2 \coloneq \mathtt{let}\ x= \mathtt{fix} (\lambda x:\tau_1.t_1)\ \mathtt{in}\ t_2$$ (using [[Let Bindings]]) 