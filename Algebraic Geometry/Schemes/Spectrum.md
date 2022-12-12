
Let $A$ be a [[Ring]]. Then let $Spec A$, be the set of all [[Prime Ideal]]s of $A$. Then we define a topology ([[Topological Space]]) on $SpecA$ as follows. 

For any ideal $a\subseteq A$, let 
$V(a)=\{p\in Spec A | a\subseteq p\}$ . This has the following properties 

* For two ideals $a$ and $b$, $V(ab) = V(a)\cup V(b)$ 
* If $\{a_i\}$ is any set of ideals, the $V(\sum_{i}a_i)=\bigcap_i V(a_i)$ 
* If $a,b$ are ideals then $V(a)\subseteq V(b)$ iff $\sqrt{a}\supseteq \sqrt{b}$ 

Therefore by taking all sets of the form $V(a)$ to be closed, this defines a topology on $SpecA$.

Next we define a [[Sheaf]] of rings $\mathcal{O}$ on $Spec A$. We denote the [[Localization]] of $A$ by $p\in SpecA$ by $A_p$. Then $\mathcal{O}(U)$ is the set of functions $s:U\rightarrow \bigsqcup_{p\in U}A_p$ s.t. $s(p)\in A_p$. With the regular restriction maps $\mathcal{O}$ defines a scheme on $Spec A$.

With these definition, the *spectrum* of $A$ is defined to be $(Spec A,\mathcal{O})$. We write $D(f)$ for the open set $SpecA\setminus V((f))$  for any $f\in A$. The spectrum of a ring is a locally [[Ringed Space]].

The spectrum of a ring satisfies the following 

* For any $p\in Spec A$, the stalk $\mathcal{O}_P$ is isomorphic to $A_p$ 
* For any $f\in A$, $\mathcal{O}(D(f))$ is isomorphic to $A_f$
* $\Gamma(SpecA,\mathcal{O})\cong A$ 

Any ring homomorphism $\varphi: A\rightarrow B$ induces a morphism of locally ringed spaces $(f,f^*):(Spec B,\mathcal{O}_{SpecB})\rightarrow (SpecA,\mathcal{O}_{SpecA}$ and conversely every such morphism is induced by a ring homomorphism. 
