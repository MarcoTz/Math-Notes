*Tuples* are a generalization of [[Pairs]], allowing an arbitrary number of terms to be combined $(t_1,\dots,t_n)$. A tuple with all elements values are usually considered values ([[Values and Normal Forms]]) and extracting the $j$-th value from a tuple is done with $t.j$. Evaluation of pairs is usually done with the following rules

$$ (v_1,\dots,v_n).j\mapsto v_j$$ 
$$ \frac{t\mapsto t^{\prime}}{t.j \mapsto t^{\prime}.j}$$
$$ \frac{t_k\mapsto t_k^{\prime}}{(v_1,\dots,v_{k-1},t_k,\dots,t_n) \mapsto (v_1,\dots,v_{k-1},t_k^{\prime},t_{k+1},\dots,t_n)}$$
When a system has a [[Type System]] , tuples usually have a tuple type $(\tau_1,\dots,\tau_n)$, which is assigned using the following rules 

$$\frac{\Gamma \vdash t_i:\tau_i \forall i}{\Gamma \vdash (t_1,\dots,t_n) : (\tau_1,\dots,\tau_n)}$$
$$ \frac{\Gamma \vdash t : (\tau_1,\dots,\tau_n)}{\Gamma \vdash t.j : \tau_j}$$