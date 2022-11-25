Given algebraic objects $X_i$ and [[Homomorphism]]s $f_j$ between those objects, they can be arraged in a *diagram*, where each homomorphism is denoted as an arrow between the objects.

For example, [[Chain Complexes]] are usually written as diagrams 

$$ \dots \xrightarrow{\partial_{n+1}} C_n \xrightarrow{\partial_n} C_{n+1} \xrightarrow{\partial_{n-1}} \dots \xrightarrow{\partial_1} C_n \xrightarrow{\partial_0} 0$$
[[Exact Sequence]]s are usually also written as diagrams

### Commutative Diagrams

A diagram is called *commutative*, if for any two paths between two objects in the diagram the resulting maps are the same. 
The simplest example is a square diagram

$$\begin{array}{ccc} A  & \xrightarrow{f} & B \\
  \downarrow g & & \downarrow h \\
  C & \xrightarrow{i} & D \end{array}$$
  This diagram is commutative if $f\circ h = i\circ g$.

### The Five-Lemma 

Given the following commutative diagram

$$ \begin{array}{} 
 A & \xrightarrow{i} & B & \xrightarrow{j} & C& \xrightarrow{k} & D & \xrightarrow{l} & E \\
\downarrow \small{\alpha} & & \downarrow \small{\beta} & & \downarrow \small{\gamma} & & \downarrow \small{\delta} & & \downarrow \small{\epsilon} \\
 A^{\prime} & \xrightarrow{i} & B^{\prime} & \xrightarrow{j} & C^{\prime}& \xrightarrow{k} & D^{\prime} & \xrightarrow{l} & E^{\prime} \\
\end{array}$$

If both rows are exact, and $\alpha$, $\beta$, $\delta$ and $\epsilon$ are isomorphisms , then $\gamma$ is also an isomorphism.