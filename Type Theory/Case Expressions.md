In a [[Type System]] with types that are defined using a set of constructors, such as [[Sum Types]], [[Records]] or [[Variant Types]], *case expressions* give a way to distinguish between the different possible shapes of terms in such a type.
Given a type $\tau$ defined by constructors $C_1,\dots,C_n$ with a number of arguments $k_1,\dots,k_n$, a case expression on $\tau$ has the form $\mathtt{case}\ t\ \mathtt{of} \{C_1(x_1,\dots,x_{k_1} \Rightarrow t_1, \dots,C_n(x_1,\dots,x_{k_n})\Rightarrow t_n\}$.
They are then typed as follows, with the type $\tau$ fixed

$$ \frac{\Gamma \vdash t_i:\tau^{\prime}\ \forall i\quad\Gamma \vdash t:\tau}{\mathtt{case}\ t\ \mathtt{of} \{C_1(x_1,\dots,x_{k_1} \Rightarrow t_1, \dots,C_n(x_1,\dots,x_{k_n})\Rightarrow t_n\}:\tau^{\prime}}$$
Evaluation ([[Evaluation Relation]]) for case expression is done similarly 

$$ \frac{t\mapsto t^{\prime}}{\mathtt{case}\ t\ \mathtt{of}\{\dots\}\mapsto \mathtt{case}\ t^{\prime}\ \mathtt{of} \{\dots\}}$$
$$ \mathtt{case}\ \mathtt{C}(t_1,\dots,t_k)\ \mathtt{of}\ \{\dots,C(x_1,\dots,x_k)\Rightarrow t,\dots\} \mapsto t[t_1/x_1,\dots,t_n/x_n]$$ ([[Substitution]])
