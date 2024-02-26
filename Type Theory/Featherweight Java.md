
*Featherweight Java* is a functional model of the Java programming language, modelling a minimal subset of the language. It is defined by the following grammar 

$$ CL \Coloneqq \mathtt{class}\ C\ \mathtt{ extends}\ C\ \{ \overline{C\ f};\ K\ \overline{M}\} \quad \mathit{Class\ Declarations}$$
$$ K \Coloneqq C(\overline{C}\ \overline{f})\ \{ \mathtt{super}(\overline{f});\ \mathtt{this}.\overline{f} = \overline{f};\} \quad \mathit{Constructor\  Declarations}$$
$$ M \Coloneqq C\ m(\overline{C}\ \overline{x})\{\mathtt{return}\ t;\} \quad \mathit{Method\ Declarations}$$
$$ t \Coloneqq x \mid t.f \mid t.m(\overline{t}) \mid \mathtt{new}\ C(\overline{t}) \mid (C)\ t$$
$$ v\Coloneqq \mathtt{new}\ C(\overline{v})$$
$$ C <: C $$
$$ \frac{C<:D \quad D<:E}{C<:E}$$
$$\frac{CT(C) = \mathtt{class}\ C\ \mathtt{extends}\ D \{ \dots \} }{C<:D}$$
We always assume a fixed *class table* $CT$ containing all defined classes and one additional class $\mathtt{Object}$ that is a superclass of all classes.
There are some additional definitions for typing and evaluation

$$ \mathtt{fields}(\mathtt{Object}) = \emptyset$$
$$\frac{CT(C) = \mathtt{class}\ C\ \mathtt{extends}\ D\ \{ \overline{C}\ \overline{f};\ K \overline{M}\}\quad B\ m(\overline{B}\ \overline{x})\{\mathtt{return}\ t;\} \in\overline{M}}{\mathtt{mtype}(m,C) = \overline{B}\rightarrow B}$$
$$\frac{CT(C) = \mathtt{class}\ C\ \mathtt{extends}\ D \{ \overline{C}\ \overline{f};\ K\ \overline{M}\quad m \text{ is not defined in }\ \overline{M}}{\mathtt{mtype}(m,C) = \mathtt{mtype}(m,D)}$$
$$\frac{CT(C) = \mathtt{class}\ C\ \mathtt{extends}\ D \{ \overline{C}\ \overline{f}; K\ \overline{M}\}\quad B\ m (\overline{B}\ \overline{x}\{\mathtt{return}\ t;\}\in\overline{M}}{\mathtt{mbody}(m,C)=(\overline{X},t)}$$
$$\frac{CT(C) = \mathtt{class}\ C\ \mathtt{extends}\ D\{\overline{C}\ \overline{f}; K\ \overline{M}\}\quad m\text{ is not defined in }\overline{M}}{\mathtt{mbody}(m,C)=\mathtt{mbody}(m,D)}$$
$$\frac{\mathtt{mtype}(m,D)=\overline{D}\rightarrow D_0\text{ implies } \overline{C}=\overline{D}\text{ and } C_0=D_0}{\mathtt{override}(m,D,C\rightarrow C_0)}$$

$$ \frac{\mathtt{fields}(C) = \overline{C}\ \overline{f}}{(\mathtt{new}\ C(\overline{v}).f_i \rightarrow v_i}$$
$$ \frac{\mathtt{body}(m,C) = (\overline{X},t_0)}{(\mathtt{new}\ C(\overline{v}).m(\overline{u})}$$
$$\frac{C<:D}{(D)(\mathtt{new}\ C(\overline{V}) \rightarrow \mathtt{new}\ C(\overline{v})}$$
$$\frac{t_0\rightarrow t_0^{\prime}}{t_0.f \rightarrow t_0^{\prime}.f}$$
$$\frac{t_0\rightarrow t_0^{\prime}}{t_0,m(\overline{t})\rightarrow t_0^{\prime}.m(\overline{t})}$$
$$\frac{t_i\rightarrow t_i^{\prime}}{v_0.m(\overline{v},t_i,\overline{t}) \rightarrow v_0.m(\overline{v},t_i^{\prime},\overline{t})}$$
$$\frac{t_i\rightarrow t_i^{\prime}}{\mathtt{new}\ C(\overline{v},t_i,\overline{t})\rightarrow \mathtt{new}\ C(\overline{v},t_i^{\prime},\overline{t})}$$
$$\frac{t_0\rightarrow t_0^{\prime}}{(C)t_0\rightarrow (C)t_0^{\prime}}$$

$$ \frac{x:C\in \Gamma}{\Gamma \vdash x:C}$$
$$ \frac{\Gamma \vdash t_0:C_0\quad \mathtt{fields}(C_0)=\overline{C}\ \overline{f}}{\Gamma \vdash t_0.f_i : C_i}$$
$$ \frac{\Gamma \vdash t_0:C_0\quad \mathtt{mtype}(m,C_0)=\overline{D}\rightarrow C\quad \Gamma \vdash \overline{t}:\overline{C} \quad \overline{C}<:\overline{D}}{\Gamma \vdash t_0.m(\overline{t}):C}$$
$$\frac{\mathtt{fields}(C)=\overline{D}\ \overline{f} \quad \Gamma \vdash \overline{t}:\overline{C}\quad \overline{C}<:\overline{D}}{\Gamma \vdash \mathtt{new}\ C(\overline{t}) : C}$$
$$\frac{\Gamma \vdash t_0:D \quad D<:C}{\Gamma \vdash (C)t_0:C}$$
$$\frac{\Gamma \vdash t_0:D \quad C<:D \quad C\neq D}{\Gamma \vdash (C)t_0:C}$$
$$\frac{\Gamma \vdash t_0:D \quad C \nless:D\quad \text{ warning }}{\Gamma \vdash (C)t_0:C}$$
$$ \frac{\overline{x}:\overline{C},\mathtt{this}:C\vdash t_0:E_0\quad E_0:C_0 \quad CT(C) = \mathtt{class}\ C\ \mathtt{extends}\ D \{\dots\} \quad \mathtt{override}(m,D,\overline{C}\rightarrow C_0)}{C_0\ m(\overline{C}\ \overline{x})\{\mathtt{return}\ t_0;\}\ \mathtt{OK}\ \mathtt{in}\ C}$$
$$ \frac{K = C(\overline{D}\ \overline{g},\overline{C}\ \overline{f})\{\mathtt{super}(\overline{g});\ \mathtt{this}.\overline{f}=\overline{f};\}\quad \mathtt{fields}(D) = \overline{D}\ \overline{g} \quad \overline{M}\ \mathtt{OK}\ \mathtt{in}\ C}{\mathtt{class}\ C\ \mathtt{extends}\ D \{ \overline{C}\ \overline{f};K\ \overline{M}\}\ \mathtt{OK}}$$

Evaluation is done with these rules and evaluation contexts 

$$ E\Coloneqq [] \mid E.F\mid E.m(\overline{f})\mid v.m(\overline{v},E,\overline{t})\mid\mathtt{new}\ C(\overline{v},E,\overline{t})\mid (C)\ E$$
Inserting a term $t$ into an evaluation context $E$ is written $E[t]$.
$$\frac{t\rightarrow t^{\prime}}{E[t]\rightarrow E[t^{\prime}]}$$
