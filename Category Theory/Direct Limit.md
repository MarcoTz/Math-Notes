Let $\langle I,\leq \rangle$ be an [[Order]]ed set, and $\{A_i|i\in I\}$ a family of objects indiced by $I$ and $f_{ij}:A_i\rightarrow A_j$ a [[Homomorphism]] for all $i\leq j$, s.t.
* $f_{ii} = \mathbb{1}_{A_i}$ 
* $f_{ik} = f_{jk}\circ f_{ij}$ for alle $i\leq j\leq k$ 
Then $\langle A_i,f_{ij} \rangle$ is called a *direct system* over $I$.

For a direct system $\{A_i,f_{ij}\}$, the *direct limit* is defined as 

$$ \underrightarrow{lim}A_i = \bigsqcup_i A_i /\sim$$ where $\sim$ is the equivalence relation ([[Relation#Equivalence Relations]]) defined by 

$$ x_i \sim x_j \Leftrightarrow f_{ik}(x_i) = f_{jk}(x_j) \text{ for some }k\in I, i\leq k,j\leq k$$

If the $A_i$ are [[Abelian Group]]s with homomorphisms $f_i : A_i\rightarrow A_{i+1}$ the direct limit of this direct system is the [[Quotient Group]] of $\bigoplus_iA_i$ by the subgroup consisting of elements $(a_1,a_2-f_1(a_1),a_3-f_2(a_2),\dots)$, so an element of $\underrightarrow{\lim}A_i$ is represented by an element $a_i\in A_i$ with $a_i\in A_i$ and $a_j\in A_j$ define the same element if both $a_i$ and $a_j$ have the same image in some $A_k$ with $k\geq max\{i,j\}$. If all $f_i$ are injevtive, we have $\underrightarrow{\lim}A_i = \bigcup_i A_i$ 