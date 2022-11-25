The *center* of a group *G* is deined as 

$Z(G) = \cap Z_G(x)$

Here $Z_G(x)$ is the centralizer of $x$ under the [[Group Actions]] of Conjugation ([[Group#Conjugation]]).
$Z(G)$ is an abelian ([[Abelian Group]]) [[Normal Subgroup]] of $G$, and contains all elements that commute with every element of $G$, i.e

$Z(G) = \{g\in G: gx=xg \forall x \in G\}$


#### Class Equation 

From the Orbit equation ([[Group Actions#Orbit Equation]]) we get the equation, where each $g_i$ represents one conjugation class.

$|G| = |Z(G)|+\sum_{i=1}^s [G:Z_G(g_i)]$

From this equation, we can see that for a group of order $p^k$ with $p$ prime, $Z(G)$ contains at least $p$ elements, and therefore it is solvable ([[Solvable Group]]). If $k=2$, the group is even abelian ([[Abelian Group]])