For a [[Type System]] with [[Subtyping]], *type coercion* is a map from terms in this type system to a different one without subtyping, such that well-typedness is preserved. This function is also defined on typing and subtyping relations, where we write $C:: T$ for a derivation $C$ with conclusion $T$.

For example, with [[Simply Typed Lambda Calculus]] with [[Records]] and subtyping, an erasure function to simply typed lambda calculus without subtyping is given by 

$$ [[\mathtt{Top}]] = \mathtt{Unit}$$
$$[[\tau_1\rightarrow \tau_2]] = [[\tau_1]]\rightarrow [[\tau_2]]$$
$$ [[\{l_1:\tau_1,\dots,l_n:\tau_n\}]] = \{l_1:[[\tau_1]],\dots,l_n:[[\tau_n]]\}$$ 
$$ [[ \frac{\quad}{\tau<:\tau} ]] = \lambda x:[[\tau]].x$$
$$[[\frac{\quad}{\tau<:\mathtt{Top}}]] = \lambda x:[[\tau]].\mathtt{unit}$$
$$[[\frac{C_1 :: \tau_1 <: \sigma_1 \quad C_2 :: \sigma_2 :: \tau_2}{\sigma_1\rightarrow \sigma_2 <: \tau_1\rightarrow \tau_2} ]] = \lambda f:[[\sigma_1\rightarrow\sigma_2]].\lambda x:[[\tau_1]].[[C_2]](f[[C_1]]\ x))$$
$$ [[\frac{\quad}{\{l_1:\tau_1,\dots.,l_{n+k}:\tau_{n+k}\}<: \{ l_1:\tau_1,\dots,l_n:\tau_n\}]] = \lambda r:\{l_1:[[\tau_1]],\dots,l_{n+k}:[[\tau_{n+k}]]\}.\{l_1=r.l_1,\dots,l_n=r.l_n\}}$$
$$ \frac{C_i :: \tau_i<:\sigma_i \forall i}{\{l_1:\tau_1,\dots,l_n:\tau_n\} <: \{l_1:\sigma_1,\dots,l_n:\sigma_n\}}]]=\lambda r:\{l_1:[[\tau_1]],\dots,l_n:[[\tau_n]]\}.\{l_1=[[C_1]](r.l_1),\dots,l_n=[[C_n]](r.l_n)\}$$
$$ \frac{\{k_1:\tau_1,\dots,k_n:\tau_n\}\text{ is a permutation of } \{l_1:\sigma_1,\dots,l_n:\sigma_m\}}{\{l_1:\tau_1,\dots,l_n:\tau_n\}<: \{l_1:\sigma_1,\dots,l_n:\sigma_n\}}]] = \lambda r:\{k_1:[[S_1]],\dots,k_n:[[S_n]]\}.\{l_1=r.l_1,\dots,l_n=r.l_n\}$$
$$ [[\frac{x:\tau\in\Gamma}{\Gamma \vdash x:\tau}]] = x$$ $$[[\frac{D_2 :: \Gamma,x:\tau_1\vdash t_2:\tau_2}{\Gamma \vdash \lambda x\tau_1.t_2 : \tau_1\rightarrow \tau_2}]] = \lambda x:[[\tau_1]].[[D_2]]$$
$$ \frac{D_1::\Gamma \vdash t_1:\tau_{11}\rightarrow \tau_{12} \quad D_2 :: \Gamma \vdash t_2 :\tau_{11}}{\Gamma \vdash t_1\ t_2 : \tau_{12}}]=[[D_1]]\ [[D_2]]$$
$$[[ \frac{D_i :: \Gamma \vdash t_i:\tau_i \forall i}{\Gamma \vdash \{ l_1=t_1,\dots,l_n=t_n\} : \{l_1:\tau_1,\dots,l_n:\tau_n\}}]] = \{l_1=[[D_1]],\dots,l_n=[[D_n]]\}$$
$$ [[\frac{D_1 :: \Gamma \vdash t_1 : \{ l_1:\tau_1,\dots,l_n:\tau_n\}}{\Gamma \vdash t_1:l_j : \tau_j}]]=[[D_1]].l_j$$
$$ [[\frac{D::\Gamma \vdash t:\tau \quad C::\tau<:\sigma}{\Gamma \vdash t:\tau}]] = [[C]] [[D]] $$ 