A sequence $\dots \rightarrow G_i \xrightarrow{\varphi_i} G_{i+1} \xrightarrow{\varphi_{i+1}} G_{i+2} \rightarrow \dots$ of of [[Homomorphism]]s (see [[Diagram]]) is called *exact*, if for each $i$ we have $Im\varphi_{i} = ker\varphi_{i+1

In the case $0\rightarrow A\xrightarrow{f} B$, $f$ has trivial kernel, so is injective 
In the case $A\xrightarrow{f} B \rightarrow 0$ $im(f)=B$, so $f$ is surjective.
In the case $0\rightarrow A \xrightarrow{f} B \rightarrow 0$, $f$ is bijective

### Short exact Sequence 

A sequence

$$ 0 \rightarrow A \xrightarrow{f} B \xrightarrow{g} C \rightarrow 0 $$
is called a *short exaqct sequence*. In this case the homomorphisms induce isomorphisms ([[Homomorphism#Monomorphisms Epimorphisms and Isomorphisms]]) $C\cong B/im(f) = B/ker(g)$.

### Splitting Lemma  

Given a short exact sequence of [[Abelian Group]]s $0\rightarrow A \xrightarrow{i} B \xrightarrow{j} C \rightarrow 0$ , the following are equivalent 
1. There is a homomorphism $p:B\rightarrow A$ with $pi = \mathbb{1}_A$
2. There is a homomorphism $s:C\rightarrow B$ with $js=\mathbb{1}_C$
3. There is an isomorphism $B\rightarrow A \oplus C$ ([[Group Products]]) that forms the following commutative diagram ([[Diagram#Commutative Diagrams]]) with the homomorphisms $A\rightarrow A\oplus C \quad a \mapsto (a,0)$ and $A\oplus C \rightarrow C \quad (a,c)\mapsto c$


![[Splitting Diagram.png]]

In this case, we say the sequence is *split*.
The Lemma also holds for nonabelian groups, but without the implications $b\Rightarrow c$ and $b\Rightarrow a$. In this case, we say the sequence splits if $b$ holds.
In both cases, the sequence being split is equivalent to $C$ being free ([[Free Groups]])

### Dual Exact Sequences 

Let $A \rightarrow B \rightarrow C \rightarrow 0$ be an exact sequence of [[Abelian Group]]s and let $G$ be any abelian group. Then the dual sequence, after appying $Hom(-,G)$, $A^*\rightarrow B^*\rightarrow C^* \rightarrow 0$ is also exact. 