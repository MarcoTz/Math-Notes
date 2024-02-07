Possible terms in programming languages are usually defined as follows 

$$ t \Coloneqq x \mid \lambda x.t \mid t\ t \mid\dots$$
(These are the terms in [[Untyped Lambda Calculus]]).
Alternatively, we can define them inductively: 
The set of terms $\mathcal{T}$ is the smallest set such that 
* $x\in\mathcal{T}$ for all variables $x$
* If $t\in\mathcal{T}$ then $\lambda x.t$ is as well
* If $t_1,t_2\in\mathcal{T}$ then $t_1\ t_2$ is as well 
(And correspondingly for any additional terms)

Or we can use inference rules:
$$ x\in\mathcal{T}$$ 
$$\frac{t\in\mathcal{T}}{\lambda x.t\in\mathcal{T}}$$
$$\frac{t_1\in\mathcal{T}\quad t_2\in\mathcal{T}}{t_1\ t_2\in\mathcal{T}}$$

Another method is a direct definition of $\mathcal{T}$ 
Let $\mathcal{T}_0=\emptyset$ and $\mathcal{T}_{i+1} = \{x | x\text{ Variable}\}\cup \{\lambda x.t | x\text{ Variable}, t\in\mathcal{T}_i\}\cup \{t_1\ t_2 | t_1,t_2\in\mathcal{T}_i\}$. Then $\mathcal{T} = \bigcup_i \mathcal{T}_i$

