Given an [[Euclidean Space]], or more generally an [[Affine Space]] $A$ s.t. the associated [[Vector Space]] is real ([[Real Numbers]]),  a *convex set*, is a subset $C$ of the space, s.t. for any two $x,y\in C$ the (unique) line through $x$ and $y$ is contained entirely in $C$.

For any convex set $C$ and points $u_1,\dots,u_n\in C$ and $t_1,\dots,t_n\in [0,1]$ with $t_1+\dots+t_n=1$ we have $t_1u_1+\dots+t_nu_n\in C$ (as opposed to only two points as in the definition). 
Such sums are called *convex combinations*.

### Convex Hull 

Given a subset $X\subseteq A$, the *convex hull* of $X$, is the smallest convex set $C\subseteq A$ containing $X$. 
We write $conv(X)$ for the convex hull of $X$.
The convex hull of $X$ is exactly the set of convex combinations of elements in $X$.


### Extreme Points

Given a point $x$ in a convex set $A$, if for any other $y,z\in A$ and $t\in (0,1)$ we have $x\neq ty+(1-t)z$ then $x$ is called an *extreme point* or sometimes *vertex* of $A$.
Since the line segment through $y,z$ can be parametrized by $ty+(1-t)z$ for $t\in(0,1)$, this means $x$ lies on no line segment connecting any two points of $A$ (except as an end point).