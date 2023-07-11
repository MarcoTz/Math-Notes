Given a [[Topological Space]] $X$ with a subspace $A$ and a chain complex $C_n$ ([[Chain Complexes]]) on $X$, let $C_n(X/A)$ be the [[Quotient Group]] $C_n(X)/C_n(A)$.
This means chains in $A$ are trivial in $C_n(X/A)$.
Since the boundary map $\partial$ always takes $C_n(A)$ to $C_{n-1}(A)$, the induced map on the quotient groups is also a boundary map, so we get a new chain complex.
The homology groups of this complex are called *relative homology groups*. 
We call the chain group the *relative chain group*, the cycles *relative cycles* and te boundaries *relative boundaries*.

The inclusion $i:A\hookrightarrow X$ and quotient map $j:X\rightarrow X/A$ ([[Topology/Quotient Space]]) induce chain maps ([[Chain Complexes#Chain maps]]) that give a [[Long Exact Sequence of Chain Complexes]]. Using this sequence, we get the following long exact sequence 

$$ \dots \rightarrow H_n(A) \xrightarrow{i_*} H_n(X) \xrightarrow{j_*} H_n(X/A) \xrightarrow{\partial} H_{n-1}(A) \xrightarrow{i_*} H_{n-1}(X) \rightarrow \dots $$ 
### Relative and Absolute Homology 

For good pairs ([[Retraction#Deformation Retraction]]) $(X,A)$, the quotient map $q:(X,A)\rightarrow (X/A,A/A)$ induces isomorphisms $H_n(X,A)\rightarrow H_n(X/A,A/A)\cong \tilde{H}_n(X/A)$ for all $n$.