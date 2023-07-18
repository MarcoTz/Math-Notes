Let $f:U\rightarrow \mathbb{R}$ be a function with $U\subseteq \mathbb{R}^n$ ([[Real Numbers]]).
Then the *partial derivative* of $f$ at $(a_1,\dots,a_n)\in U$ in direction $x_i$ is defined as 

$$ \frac{\partial}{\partial x_i} = \lim_{h\rightarrow 0} \frac{f(a_1,\dots,a_{i-1},a_i+h,a_{i+1},\dots,a_n) - f(a_1,\dots,a_n)}{h}$$ 
If the partial derivative of $f$ exists in all directions $x_1,\dots,x_n$ then $f$ is called *total differentiable* at $(a_1,\dots,a_n)$ .
We write $f\in C^n(U)$ similarly to [[Differentiable Function]]s if $f$ is $n$-times total differentiable.
If $f$ is $C^2$ ([[Differentiable Function]]), then we have 
$$ \frac{\partial^2f}{\partial x_i \partial x_j} = \frac{\partial^2 f}{\partial x_j \partial x_i}$$ 