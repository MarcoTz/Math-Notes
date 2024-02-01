When dealing with a calculus containing variables (for example [[Untyped Lambda Calculus]]), we always have to make sure variables are distinct, which may require $\alpha$-renaming. 
An alternative to $\alpha$-renaming is a *nameless representation* of variables, where variables do not have names $x,y,\dots$ but indices $0,1,\dots$. These indices are called *deBruijn indices*.

Terms are then defined as follows (using the untyped lambda calculus forms)
$\mathcal{T}$ is the smallest family of sets $\{\mathcal{T}_0,\mathcal{T}_1,\dots\}$ such that 
* $k\in\mathcal{T}_n$ for $0\neq k <n$
* If $t_1\in\mathcal{T}_n$ and $n>0$ then $\lambda.t_1\in\mathcal{T}_{n-1}$ 
* If $t_1,t_2\in\mathcal{T}_n$ then $(t_1\ t_2)\in\mathcal{T}_n$ 
Terms in $\mathcal{T}_n$ are ones with at most $n$ free variables.
This definition can be adjusted to different calculi.

For free variables, we use a *naming context* $\Gamma$ containing a list of variable name $x,y,\dots$ in order, and the index of a variable is then the place it occurs in. 
In order to correctly translate from and to a named representation, we need shifting to keep the indices correct 

For a term $t$, the $d$-place shift with cutoff $c$ is defined as 
$$ \uparrow^d_c(k) = k\text{ if } k<c$$ 
$$ \uparrow^d_c(k) = k+d \text{ if } k>c$$$$ \uparrow^d_c(\lambda.t) = \lambda.\uparrow^d_{c+1}(t)$$
$$\uparrow^d_c(t_1\ t_2) = \uparrow^d_c(t_1)\ \uparrow^d_c(t_2)$$

Using shifting, substitution on nameless terms is defined as 
$$k[s/j] = s \text{ if } k=j$$ 
$$k[s/j] = k \text{ if } k\neq j$$
$$ \lambda.t [s/j] = \lambda.[\uparrow^1(s)]t$$ 
$$(t_1\ t_2)[s/j] = (t_1[s/j])\ (t_2[s/j])$$ 
Evaluation of lambda expressions then also has to be changed to 
$$ (\lambda.t_1)\ t_2 \mapsto \uparrow^{-1}(t_2[\uparrow^1(t_1)/0])$$
