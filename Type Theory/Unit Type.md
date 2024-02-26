The *Unit Type* in a [[Type System]] is a type with a single trivial term $\mathtt{unit}$, or sometimes just written $\mathtt{u}$.
It always has a typing rule of the form $\Gamma \vdash \mathtt{unit}:\mathtt{Unit}$ and can be used to define *sequencing*: $t_1;t_2 = (\lambda x:\mathtt{Unit}.t_2)t_1)$ ([[Simply Typed Lambda Calculus]]), where first $t_1$ is evaluated ([[Evaluation Relation]]) and then $t_2$. This is a [[Derived Form]] and usually only used with [[Side effects]].