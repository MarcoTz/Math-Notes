Types of lists can be added to a [[Type System]] with two constructors $\mathtt{Nil}$ taking no arguments (empty list) and a constructor $\mathtt{Cons}$ appending an element to the beginning of a list. Lists are then  values when they are either empty ($\mathtt{Nil}$) or both arguments of $\mathtt{Cons}$ are values ([[Values and Normal Forms]]).
They are typed as 
$$ \Gamma \vdash \mathtt{Nil} : \mathtt{List}(\tau)$$
$$\frac{\Gamma\vdash t_1:\tau\quad \Gamma \vdash t_2:\mathtt{List}(\tau)}{\Gamma\vdash\mathtt{Cons}(t_1,t_2):\mathtt{List}(\tau)}$$
Evaluation ([[Evaluation Relation]]) for lists is then done with 

$$ \frac{t_1\mapsto t_1^{\prime}}{\mathtt{Cons}(t_1,t_2) \mapsto \mathtt{Cons}(t_1^{\prime},t_2)}$$
$$ \frac{t_2\mapsto t_2^{\prime}}{\mathtt{Cons}(v,t_2)\mapsto \mathtt{Cons}(v,t_2^{\prime})}$$
Other computations with lists is usually done with [[Case Expressions]].