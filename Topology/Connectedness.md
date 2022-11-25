A [[Topological Space]] $X$, is said to be *connected*, if there are no two nonempty open subsets $A,B\subseteq X$ with $A\cup B = X$ and $A\cap B = \emptyset$.
Subsets of $X$ are said to be connected, if they are connected as subspaces of $X$.

For a topological space $X$, the following are equivalent
1. $X$ is connected 
2. The only subsets of $X$ that are open and closed are $X$ and $\emptyset$
3. The only subsets of $X$ with empty boundary are $X$ and $\emptyset$
4. $X$ cannot be written as the union of two nonempty separated sets (i.e. their closures are disjoint)
5. Every continous function $f:X\rightarrow \{0,1\}$ is constant

If $X$ is not connected, we call maximum (ordered by inclusion) connected subsets of $X$, the *connected components* of $X$.

### Local Connectedness

A topological space $X$ is said to be *locally connected*, if for each $x\in X$, there is an open neighborhood of $x$ that is connected.
Any connected space is also locally connected

### Weak Connectedness

A topological space $X$ is said to be *weakly locally connected* at a point $x\in X$ if each open neighborhood of $x$, contains a neighborhood of $x$, that is connected.

A space is locally connected iff it is weakly locally connected.