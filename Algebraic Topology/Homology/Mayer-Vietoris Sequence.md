Let $X$ be a [[Topological Space]] with subspaces $A$ and $B$ s.t. $X=intA\cup intB$. Then there is an [[Exact Sequence]] on [[Singular Homology]] of the following form 

$$\dots H_n(A\cap B) \xrightarrow{\Phi} H_n(A) \oplus H_n(B) \xrightarrow{\Psi} H_n(X) \xrightarrow{\partial} H_{n-1}(A\cap B) \rightarrow \dots \rightarrow H_n(X)\rightarrow 0$$

The [[Homomorphism]]s $\Phi$ and $\Psi$ are induced by the two homomomorphisms $\varphi : C_n(A) \rightarrow C_n(B) \quad x \mapsto (x,-x)$ and $\psi : C_n(A)\oplus C_n(B) \rightarrow C_n(A+B) \quad (x,y)\mapsto x+y$, where $C_n(A+B)$ is the chain group generated by elements $a+b$ with $a\in A$ and $b\in B$ .

The same sequence also exists for reduced homology groups ([[Homology#Reduced Homology]]) by augmenting the sequence of chain groups.

More generally, this sequence also exists, if $X=A\cup B$ s.t. $A$ and $B$ are deformation retracts ([[Retraction#Deformation Retraction]]) of $U$ and $V$ where $U\cap V$ also deformation retracts to $A\cap B$.


### Relative Mayer Vietoris Sequence 

Given a pair of spaces $(X,Y) = (A\cup B,C\cup D)$ s.t. $C\subseteq A$, $D\subseteq B$, $X=intA\cup intB$ and $Y=int C\cup int D$ we get the *relative Mayer Vietoris Sequence*

$$ \dots \rightarrow H_n(A\cap B, C\cap D)\xrightarrow{\Phi} H_n(A,C)\oplus H_n(B,D) \xrightarrow{\Psi} H_n(X,Y)\xrightarrow{\partial}\dots$$

### [[Cohomology]]

For cohomology we have the absolute sequence

$$ \dots H^n(X;G) \xrightarrow{\psi} H^n(A;G) H^n(A;G)\oplus H^n(B;G) \xrightarrow{\Phi} H^n(A\cap B;G)\rightarrow H^{n+1}(X;G)\rightarrow \dots $$ 
And the relative sequence

$$ \dots H^n(X,Y;G) \rightarrow H^n(A,C;G) \oplus H^n(B,D;G) \rightarrow H^n(A\cap B,C\cap D; G) \rightarrow \dots $$ 

