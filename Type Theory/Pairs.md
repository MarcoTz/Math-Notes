Pairs are terms that combine two other terms, usually written as $(t_1,t_2)$. A pair is considered to be a value when both terms are values ([[Values and Normal Forms]]). To obtain one of them we write $p.\mathtt{fst}$ or $p.\mathtt{snd}$ which evaluates in the following way (in call-by-value [[Evaluation Orders in Lambda Calculus]])

$$\frac{t_1\mapsto t_1^{\prime}}{(t_1,t_2)\mapsto (t_1^{\prime},t_2)} $$

$$ \frac{t_2\mapsto t_2^{\prime}}{(t_1,t_2)\mapsto (t_1,t_2^{\prime})}$$ 
$$ \frac{t_1\mapsto t_1^{\prime}}{t_1.\mathtt{fst} \mapsto t_1^{\prime}.\mathtt{fst}}$$ 
$$\frac{t_1\mapsto t_1^{\prime}}{t_1.\mathtt{snd}\mapsto t_1^{\prime}.\mathtt{snd}}$$
$$ (v_1,v_2).\mathtt{fst} \mapsto v_1$$
$$ (v_1,v_2).\mathtt{snd}\mapsto v_2$$


When typing is added ([[Simply Typed Lambda Calculus]]), there is usually a *product type* $\tau_1\times \tau_2$ for pairs with the rules 
$$ \frac{\Gamma \vdash t_1:\tau_1\quad \Gamma \vdash t_2:\tau_2}{\Gamma \vdash (t_1,t_2) : \tau_1\times\tau_2}$$
$$ \frac{\Gamma\vdash t : \tau_1\times\tau_2}{\Gamma \vdash t.\mathtt{fst} : \tau_1}$$
$$ \frac{\Gamma\vdash t:\tau_1\times \tau_2}{\Gamma \vdash t.\mathtt{snd}:\tau_2}$$