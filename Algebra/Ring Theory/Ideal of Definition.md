Let $(\mathfrak{X},\mathcal{O}_{\mathfrak{X}})$ be a [[Noetherian Formal Scheme]]. A [[Sheaf of Ideals]] $\mathfrak{I} \subseteq \mathcal{O}_{\mathfrak{X}}$ is called an *ideal of definition* for $\mathfrak{X}$ if $Supp \mathcal{O}_{\mathfrak{X}}/\mathfrak{I} = \mathfrak{X}$ and the locally [[Ringed Space]] $(\mathfrak{X},\mathcal{O}_{\mathfrak{X}}/\mathfrak{I})$ is a [[Noetherian Scheme]]

For a noetherian formal scheme $(\mathfrak{X},\mathcal{O}_{\mathfrak{X}})$ we have 
* If $\mathfrak{I}_1$ and $\mathfrak{I}_2$ are two ideals of definition, there are $m,n >0$ with $\mathfrak{I}_1 \supseteq \mathfrak{I}_2^m$ and $\mathfrak{I}_2 \supseteq \mathfrak{I}_1^n$ 
* There is a unique largest ideal of definition $\mathfrak{I}$ characterized by the fact that $(\mathfrak{X},\mathcal{O}_{\mathfrak{X}}/\mathfrak{I})$ is reduced ([[Properties of Schemes]]). In particular, ideals of definition exist
* If $\mathfrak{I}$ is an ideal of definition, then $\mathfrak{I}^n$ is as well, for any $n>0$ 
If furthermore, $\mathfrak{I}$ is an ideal of definition and for $n>0$, $Y_n:=(\mathfrak{X},\mathcal{O}_{\mathfrak{X}}/\mathfrak{I}^n)$, then
* If $\mathfrak{F}$ is a [[Coherent Sheaf of modules]], then $\mathcal{F}_n = \mathfrak{F}/\mathfrak{I}^n\mathfrak{F}$ is a coherent sheaf of motules and $\mathfrak{F} \cong \underleftarrow{\lim}\mathcal{F}_n$ 
* If for each $n$ $\mathcal{F}_n$ is a coherent $\mathcal{O}_{Y_n}$-module and $\varphi_{n^{\prime}n}:\mathcal{F}_{n^{\prime}} \rightarrow \mathcal{F}_n$ are surjective maps making $\{\mathcal{F}_n\}$ into an inverse system ([[Inverse Limit]]). If furthermore for each $n^{\prime} \geq n$, $ker \varphi_{n^{\prime}n} = \mathfrak{I}^n\mathcal{F}_{n^{\prime}}$, then $\mathfrak{F} = \underleftarrow{\lim} \mathcal{F}_n$ is a coherent $\mathcal{O}_{\mathfrak{X}}$-module and for each $n$, $\mathcal{F}_n \cong \mathfrak{F}/\mathfrak{I}^n\mathfrak{F}$ 