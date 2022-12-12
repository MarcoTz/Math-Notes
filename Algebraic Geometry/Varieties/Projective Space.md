Given a $K$-[[Vector Space]] $V$, the projective space $\mathbb{P}(V)$ is the set of equivalence classes ([[Relation#Equivalence Classes]]) of $V\setminus \{0\}$ under the identification $\lambda v \sim v$ for all $\lambda \in K$.
Alternatively, $\mathbb{P}(V)$ is the set of $1$-dimensional subspaces of $V$. 
Elements of $\mathbb{P}(V)$ are called points. For any representant of a point is write as a $(n+1)$-tuple $(a_0:\dots:a_n)$, called *homogeneous coordinates* of the point.

For $V = K^n$, we write $\mathbb{P}^n(K)$ or $K\mathbb{P}^n$ for $\mathbb{P}(V)$. 

If $V$ is a [[Topological Space]], $\mathbb{P}^n(V)$ is also a topological space, with the topology induced by $V$ under the quotient map.

### Affine Covering

For any $0\leq i\leq n$, the subset $\{x_i\neq 0\}\subseteq \mathbb{P}^n$ is isomorphic as a [[Variety]] to $\mathbb{A}^n$ via the map 
$$ (a_0:\dots:a_n) \mapsto (\frac{a_0}{a_i},\dots,\frac{a_n}{a_i})$$ with the coordinate $a_i$ omitted.

### [[Cohomology]]

We have the following

$$ H^*(\mathbb{R}\mathbb{P}^n;\mathbb{Z}_2) \cong \mathbb{Z}_2[\alpha]/(\alpha^{n+1}) \quad H^*(\mathbb{R}\mathbb{P}^{\infty};\mathbb{Z}_2) \cong\mathbb{Z}_2[\alpha] \quad |\alpha| = 1$$
$$ H^*(\mathbb{C}\mathbb{P}^n;\mathbb{Z}) \cong \mathbb{Z}[\alpha]/(\alpha^{n+1}) \quad H^*(\mathbb{C}\mathbb{P}^{\infty};\mathbb{Z}) \cong \mathbb{Z}[\alpha] \quad |\alpha|=2$$
