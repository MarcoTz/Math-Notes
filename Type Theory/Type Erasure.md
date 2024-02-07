When a typed programming language (such as [[Simply Typed Lambda Calculus]]) is evaluated, the actual types of terms are no longer needed.
Thus usually terms are translated into a different language without types (for example [[Untyped Lambda Calculus]]) before evaluation. This is called *type erasure*.
The transformation looks as follows 
$$ \mathtt{erase}(x) = x$$
$$ \mathtt{erase}(\lambda x:T_1.t_2) = \lambda x.\mathtt{erase}(t_2)$$
$$\mathtt{erase}(t_1\ t_2) = \mathtt{erase}(t_1)\ \mathtt{erase}(t_2)$$

Then if $t\mapsto t^{\prime}$ in the typed evaluation, then $\mathtt{erase}(t)\mapsto \mathtt{erase}(t^{\prime})$. 
And if $\mathtt{erase}(t)\mapsto m^{\prime}$ in the untyped relation, then there is a typed term $t^{\prime}$ with $t\mapsto t^{\prime}$ and $\mathtt{erase}(t^{\prime}) = m^{\prime}$.
An untyped term $t$ is called *typable*, if there is a typed term that erases to $t$.