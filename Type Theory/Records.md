*Records* are a generalization of [[Tuples]], giving labels to terms: $\{l_1 = t_1,\dots,l_n=t_n\}$. When all terms in a record are values ([[Values and Normal Forms]]), the record is also considered a value, and obtaining the value with label $l_i$ is done with $r.l_i$. 
Evaluation of records is done with the following rules 

$$ \{l_1=v_1,\dots,l_n=v_n\}.l_j \mapsto v_j$$
$$\frac{t\mapsto t^{\prime}}{t.l_j \mapsto t^{\prime}.l_j}$$
$$\frac{t_k\mapsto t_k^{\prime}}{\{l_1=v_1,\dots,l_{k-1}=v_{k-1},l_k=t_k,\dots,l_n=t_n\}\mapsto \{l_1=v_1,\dots,l_{k-1}=v_{k-1},l_k=t_k^{\prime},l_{k+1}=t_{k+1},\dots,l_n=t_n\}}$$

When we have a [[Type System]], records have a *record type* $\{l_1:T_1,\dots,l_n:T_n\}$ which is inferred with the rules 

$$ \frac{\Gamma\vdash t_i:T_i \forall i}{\Gamma \vdash \{l_1=t_1,\dots,l_n=t_n\} : \{l_1:T_1,\dots,l_n:T_n\}}$$
$$ \frac{\Gamma\vdash t:\{l_1:T_1,\dots,l_n:T_n\}}{\Gamma \vdash t.l_j : T_j}$$
[[Subtyping]] for records comes in three parts

$$ \{ l_1:\tau_1,\dots,l_{n+k}:\tau_{n+k}\} <: \{ l_1:\tau_1,\dots,l_n:\tau_n\}$$
$$\frac{\tau_i<:\sigma_i \forall i}{\{l_1:\tau_1,\dots,l_n:\tau_n\}<:\{l_1:\sigma_1,\dots,l_n:\tau_n\}}$$$$\frac{\{k_1:\tau_1,\dots,k_n:\tau_n\}\text{ is a permutation of } \{l_1:\sigma_1,\dots,l_n:\sigma_n\}}{\{k_1:\tau_1,\dots,k_n:\tau_n\}<:\{l_1:\sigma_1,\dots,l_n:\sigma_n:\sigma_i\}}$$ 