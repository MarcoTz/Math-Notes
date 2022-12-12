
A *Convex Polytope* $P$ in $\mathbb{R}^n$ is the convex hull ([[Convexity]]) of finitely many points in $\mathbb{R}^n$. The extreme points of this set are called the *vertices* of $P$.
Equivalently, a polytope $P$ is the intersection of finitely many half-spaces $\mathbb{H}_1,\dots,\mathbb{H}_n$ of $\mathbb{R}^n$ ([[Euclidean Space#Half-Spaces]]). This intersection needs to be closed, otherwise the convexity is not guaranteed. The associated hyperplanes of the half-spaces are called *supporting hyperplanes*.

The dimension of the smallest subspace of $\mathbb{R}^n$ containing $P$ is called the *Dimension of $P$*, written $dim(P)$. This is always equaal to the number of vertices of $P$ minus 1.

### Faces

Given a polytope $P$ with vertices $v_1,\dots,v_n$, removing any number of vertices defines another polytope $P^{\prime}$ with the same vertices, but some removed. Any such polytope is called a *face* of $P$.
If a face $F$ of $P$ is obtained by removing $k$ vertices of $P$, we have $dim(F)=dim(P)-k$.
$0$-dimensional faces are exactly the *vertices* of $P$. $1$-dimensinoal faces are called *edges*, and $dim(P)-1$-dimensinal faces are called *facets*.
There is a $1-1$ correspondence between facets of $P$ and supporting hyperplanes of $P$.