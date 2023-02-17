Let $I$ be an [[Order]]ed set and $\{A_i\}_{i\in I}$ a family of [[Group]]s s.t there is a family of [[Group Homomorphism]]s $f_{ij}:A_j\rightarrow A_i$ for all $i\leq j$ with the following properties

* $f_{ii} = \mathbb{1}_{A_i}$
* $f_{ij} = f_{ij}\circ f_{jk}$ for all $i\leq j\leq k$ 

Then $(\{A_i\}_{i\in I}, \{f_{ij}\}_{i\leq j\in I})$ is called an *inverse system*. 

Given such an inverse system, the *inverse limit* of this system is defined by the following 

$$ A = lim_{\leftarrow i\in I}A_i = \{\overrightarrow{a} \in \Pi_{i\in I} A_i | a_i = f_{ij}(a_j) \text{ for all } i\leq j \in I\} $$

There are natural projections $\pi_i:A\rightarrow A_i$ mapping $\overrightarrow{a}$ to its component $a_i$.
For an inverse system we have a map $\delta:\Pi_i A_i \rightarrow \Pi_i A_i$ by $\delta(\dots,g_i,\dots) = \delta(\dots,g_i-\alpha_{i+1}(g_{i+1}),\dots)$ and we write $\underleftarrow{\lim}^1 = coker(\delta)$. Then we have an exact sequence
$$ 0\rightarrow \underrightarrow{\lim}A_i \rightarrow \Pi_iA_i \xrightarrow{\delta} \Pi_i A_i \rightarrow \underleftarrow{\lim}^1 A_i \rightarrow 0 $$ and we have the following properties 

* If all $f_i$ are isomorphisms $\underleftarrow{\lim}A_i \cong A_0$ and $\underleftarrow{\lim}^1 A_i = 0$.
* If all $f_i$ are zero, $\underleftarrow{\lim}A_i = \underleftarrow{\lim}^1A_i = 0$ 
* Deleting a finite number of terms at the end of the sequence $\dots \rightarrow A_i \rightarrow A_0$ or replacing the sequence by a subsequence does not affect $\underleftarrow{\lim}A_i$ and $\underleftarrow{\lim}^1A_i$  