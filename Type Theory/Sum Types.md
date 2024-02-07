In a programming language with a [[Type System]], a *sum type*, also called the *union type* combines all terms of two different types $\tau_1$ and $\tau_2$ with a tag, usually $\mathtt{inl}$ or $\mathtt{inr}$ which then have type $\tau_1 + \tau_2$, or sometimes $\mathtt{Either}(\tau_1,\tau_2)$. 
Sum values ([[Values and Normal Forms]]) are just $\mathtt{inl}\ v$ or $\mathtt{inr}\ v$ 
The typing and evaluation ([[Evaluation Relation]]) rules are then

$$ \frac{t_1\mapsto t_1^{\prime}}{\mathtt{inl}\ t_1 \mapsto \mathtt{inl}\ t_1^{\prime}}$$
$$ \frac{t_1\mapsto t_1^{\prime}}{\mathtt{inr}\ t_1 \mapsto \mathtt{inr}\ t_1^{\prime}}$$
$$ \frac{\Gamma \vdash t:\tau_1}{\Gamma \vdash \mathtt{inl}\ t:\tau_1+\tau_2}$$
$$ \frac{\Gamma\vdash t:\tau_2}{\Gamma \vdash \mathtt{inr}\ t : \tau_1+\tau_2}$$
Note that in the typing rules one of the two types $\tau_1$ or $\tau_2$ is arbitrary. 
In order to have unique types in a type system, sums need to be combined with [[Ascription]].