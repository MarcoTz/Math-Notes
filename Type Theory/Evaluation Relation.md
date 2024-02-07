Given a language of terms $t$ (such as [[Untyped Lambda Calculus]]) an evaluation relation is a binary relation ([[Relation]]) on terms, usually written $t\mapsto t^{\prime}$ if $t$ *evaluates to* $t^{\prime}$ in one step and $\mapsto$ is usually defined with rules such as 
$$ (\lambda x. t_1)\ t_2 \mapsto t_1[t_2/x]$$ 
The *multi-step* evaluation relation $t\mapsto^* t^{\prime}$ is defined as the transitive closure of $\mapsto$, that is $t$ is evaluated to $t^{\prime}$ in zero or more steps.

Rules that directly operate on terms such as the one above are often called *evaluation rules* while ones that only allow evaluating subexpressions such as
$$ \frac{t_1\mapsto t_1^{\prime}}{t_1\ t_2 \mapsto t_1^{\prime}\ t_2}$$ are called *congruence rules*.