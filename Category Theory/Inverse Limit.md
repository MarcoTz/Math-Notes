Let $I$ be an [[Order]]ed set and $\{A_i\}_{i\in I}$ a family of [[Group]]s s.t there is a family of [[Group Homomorphism]]s $f_{ij}:A_j\rightarrow A_i$ for all $i\leq j$ with the following properties

* $f_{ii} = \mathbb{1}_{A_i}$
* $f_{ij} = f_{ij}\circ f_{jk}$ for all $i\leq j\leq k$ 

Then $(\{A_i\}_{i\in I}, \{f_{ij}\}_{i\leq j\in I})$ is called an *inverse system*. 

Given such an inverse system, the *inverse limit* of this system is defined by the following 

$$ A = lim_{\leftarrow i\in I}A_i = \{\overrightarrow{a} \in \Pi_{i\in I} A_i | a_i = f_{ij}(a_j) \text{ for all } i\leq j \in I\} $$

There are natural projections $\pi_i:A\rightarrow A_i$ mapping $\overrightarrow{a}$ to its component $a_i$ 