
Let $C$ be a chain complex ([[Chain Complexes]]) of [[Abelian Group]]s, then there are natural short [[Exact Sequence]]s for all $n$ and $G$ which split ([[Exact Sequence#Splitting Lemma]].

$$ 0 \rightarrow H_n(C) \otimes  G \rightarrow H_n(C;G) \rightarrow Tor(H_{n-1}(C),G)\rightarrow 0$$ where $Tor(A,B) = H_1(F,B)$ where $F$ is any free resolution ([[Free Groups#Free resolution]]) of $A$. It has the following properties 

* $Tor(A,B) \cong Tor(B,A)$
* $Tor(\bigoplus_i A_i,B) \cong \bigoplus_i Tor(A_i,B)$
* $Tor(A,B)=0$ if $A$ or $B$ is torsion-free
* $Tor(A,B)\cong Tor(T(A),B)$ where $T(A)$ is the torsion subgroup of $A$
* $Tor(\mathbb{Z}_n,A) \cong Ker(A\xrightarrow{n} A)$ 
* If $0\rightarrow B\rightarrow C\rightarrow D \rightarrow 0$ is exact, then $0\rightarrow Tor(A,B)\rightarrow Tor(A,C)\rightarrow Tor(A,D)\rightarrow A\otimes B \rightarrow A\otimes C \rightarrow A\otimes D \rightarrow 0$ is as well