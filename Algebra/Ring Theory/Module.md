Given a commutative [[Ring]] $R$, a $R$-module is an [[Abelian Group]] $M$ with a mapping $R\times M\rightarrow M$ s.t. the following holds for $r,r_1,r_2\in R$ and $m,m_1,m_2\in M$ 

* $r_1(r_2m) = (r_1r_2)m$
* $(r_1+r_2)m=r_1m+r_2m$
* $r(m_1+m_2)=rm_1+rm_2$
### Free Modules 

A module is called *free* if there is a subset $E\subseteq M$, called a *generating set* or *basis* with the following properties

* $E$ generates $M$, i.e. for each $m\in M$ there are some $e_1,\dots,e_n\in E$ and $r_1,\dots,r_n\in R$ with $m=r_1e_1+\dots+r_ne_n$ 
* Elements of $E$ are linearly independent, i.e. if $r_1e_1+\dots+r_ne_n=0$ for some $e_1,\dots,e_n\in E$ and $r_1,\dots,r_n\in R$ then $r_1=\dots=r_n=0$ 

Every [[Vector Space]] is a free module.