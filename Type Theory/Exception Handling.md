*Exception Handling* is a way to allow programs to recover from a fail state, for example a division by $0$.
To add this to a programming language, we need an additional term $\mathtt{error}$ to indicate a fail-state, or alternatively a term $\mathtt{raise}\ t$ such that the error can contain some additional information in $t$, and a way to handle errors, $\mathtt{try} \ t\ \mathtt{with}\ t$.
These are then evaluated ([[Evaluation Relation]]) as follows 

$$ \mathtt{error}\ t \mapsto \mathtt{error}$$
$$ t\ \mathtt{error} \mapsto \mathtt{error}$$
$$ (\mathtt{raise}\ v)\ t \mapsto \mathtt{raise}\ v$$
$$ v_1\ (\mathtt{raise}\ v_2) \mapsto \mathtt{raise}\ v_2 $$
$$\frac{t_1\mapsto t_1^{\prime}}{\mathtt{raise}\ t_1 \mapsto \mathtt{raise}\ t_1^{\prime}}$$
$$\mathtt{raise}\ (\mathtt{raise}\ v) \mapsto \mathtt{raise}\ v$$
These are the rules for call-by-value ([[Evaluation Orders in Lambda Calculus]]) and have to be adjusted for different evaluation orders.
However, the rules for applications ([[Untyped Lambda Calculus]]) have to allow $\mathtt{error}$ or $\mathtt{raise}$ to always be evaluated, as we have to stop computation when an error occurs. Depending on the other rules in the systems some more rules for $\mathtt{error}$ of $\mathtt{raise}$ need to be added).

$$ \frac{t_1\mapsto t_1^{\prime}}{\mathtt{try}\ t_1\ \mathtt{with}\ t_2 \mapsto \mathtt{try}\ t_1^{\prime}\ \mathtt{with}\ t_2}$$
$$ \mathtt{try}\ \mathtt{error}\ \mathtt{with}\ t_2 \mapsto t_2$$
$$ \mathtt{try}\ v\ \mathtt{with}\ t \mapsto v$$

$$\mathtt{try}\ \mathtt{raise}\ v\ \mathtt{with}\ t_2 \mapsto t_2\ v$$
In the case we use $\mathtt{raise} v$, the value $v$ is passed to $t_2$ as a function application.

If we also have a [[Type System]], typing with $\mathtt{error}$ and $\mathtt{try}$ are straightforward

$$ \Gamma \vdash \mathtt{error}:\tau$$
$$ \frac{\Gamma \vdash t_1:\tau \quad \Gamma \vdash t_2:\tau}{\Gamma \vdash \mathtt{try}\ t_1\ \mathtt{with}\ t_2:\tau}$$
$\mathtt{error}$ can have any type, so it can be used anywhere.
If we use $\mathtt{raise}$ this needs to be changed slightly with a fixed type $\tau_{err}$ for the term bound by $\mathtt{raise}$
$$\frac{\Gamma \vdash t_1 : \tau_{err}}{\Gamma \vdash \mathtt{raise}\ t_1 : \tau}$$
$$ \frac{\Gamma \vdash t_1:\tau \quad \Gamma \vdash t_2:\tau_{err}\rightarrow \tau}{\Gamma \vdash \mathtt{try}\ t_1\ \mathtt{with}\ t_2 : \tau}$$

There are different options for the type $\tau_{err}$:
* Often $\tau_{err}$ is just the type of natural numbers, returning an error code
* Alternatively it can be a string containing an error text
* It can also be a variant type ([[Variant Types]]) with different labels for different kinds of errors.
* It can also be an extensible variant type, that is a variant type where new labels can be added dynamically, to define new errors.