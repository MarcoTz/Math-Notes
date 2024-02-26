*Intersections* and *Unions* of types are features that some [[Type System]]s with [[Subtyping]] have.
The intersection of $\tau$ and $\sigma$ is written as $\tau \wedge \sigma$ and is a subtype of both $\sigma$ and $\tau$, while their union is written as $\tau \vee \sigma$ and is a supertype of both 

$$ \tau \wedge \sigma <: \tau$$
$$ \tau\wedge \sigma <: \sigma$$
$$ \frac{\tau^{\prime}<:\tau\quad \tau^{\prime}<:\sigma}{\tau^{\prime}<:\tau\wedge\sigma}$$
$$ \tau\rightarrow \sigma_2 \wedge \tau\rightarrow\sigma_2 <: \tau\rightarrow (\sigma_1\wedge\sigma_2)$$
$$ \tau <: \tau \vee \sigma$$
$$\sigma <: \tau \vee \sigma$$
$$\frac{\tau<:\tau^{\prime}\quad \sigma<:\tau^{\prime}}{\tau\vee\sigma <:\tau^{\prime}}$$
$$\tau_1 \rightarrow \sigma \vee \tau_2\rightarrow \sigma <: (\tau_1 \vee \tau_2)\rightarrow \sigma$$
