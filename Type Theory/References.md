*References* are a simple kind of side effect ([[Side effects]]) in programming languages.
They allow creating a reference to a memory cell (of a certain type if there is a [[Type System]]), that can be assigned, or read from.
To add references to a programming languages, one needs a way to create references $\mathtt{ref}\ t$, dereference (i.e. read) $!t$ and assign a reference $t\coloneq t$. 
In order to correctly access references we also need a store location term $l$ that is an address in memory. This is usually not available directly to programmers and only appears in an intermediate language.
These addresses are then the only new values ([[Values and Normal Forms]]) needed are the store locations $l$.
If there is a type system, there is a new type constructor $\mathtt{Ref}\ \tau$ for references of type $\tau$.

For typing there also needs to be a way to type references, which cannot be done directly because there might be cyclic references. This is done with a *store typing* $\Sigma$ containing types $l:\tau$ for locations. Typing is then written as $\Gamma \mid \Sigma \vdash t :\tau$ 
The typing rules for references are 
$$ \frac{\Sigma(l) = \tau}{\Gamma\mid \Sigma \vdash l :\mathtt{Ref}\ \tau}$$
$$ \frac{\Gamma \mid \Sigma \vdash t: \tau}{\Gamma\mid\Sigma\vdash \mathtt{ref}\ t : \mathtt{Ref}\ \tau}$$
$$\frac{\Gamma\mid\Sigma\vdash t:\mathtt{Ref}\ \tau}{\Gamma\mid\Sigma\vdash !t:\tau} $$
$$\frac{\Gamma\mid\Sigma\vdash t_1 : \mathtt{Ref}\ \tau \quad \Gamma\mid\Sigma\vdash t_2:\tau}{\Gamma\mid\Sigma\vdash t_1\coloneq t_2 : \mathtt{Unit}} $$
We here use the [[Unit Type]], to denote an assignment does not return anything.
Note that other typing rules of a system then also need to be adjusted to correctly propagate changes in $\Sigma$. In particular, when a premise has the form $\mathtt{ref}\ t$ its type needs to be added to $\Sigma$

Similarly, for evaluation ([[Evaluation Relation]]), stores $\mu$ need to be added, containing elements $l=v$ of the store at location $l$, and evaluation is then written as $t \mid \mu \mapsto t^{\prime}\mid\mu^{\prime}$ if $t$ evaluates to $t^{\prime}$ with a given store $\mu$ and returns a new store $\mu^{\prime}$.
Evaluation is then done with the following rules 

$$ \frac{l\notin \mu}{\mathtt{ref}\ v \mid \mu \mapsto t\mid(\mu,l=v)}$$
$$ \frac{t\mid\mu\mapsto t^{\prime}\mid\mu^{\prime}}{\mathtt{ref}\ t\mid\mu\mapsto \mathtt{ref}\ t^{\prime}\mid\mu^{\prime}}$$
$$\frac{\mu(l)=v}{!l\mid\mu \mapsto v\mid\mu}$$
$$\frac{t\mid\mu\mapsto t^{\prime}\mid\mu^{\prime}}{!t\mid\mu \mapsto !t^{\prime}\mid\mu^{\prime}}$$
$$ l\coloneq v\mid\mu \mapsto \mathtt{unit}\mid \mu[v/l]$$
$$ \frac{t_1\mid\mu\mapsto t_1^{\prime}\mid\mu^{\prime}}{t_1\coloneq t_2\mid\mu \mapsto t_1^{\prime}\coloneq t_2\mid\mu^{\prime}}$$
$$ \frac{t_2\mid\mu\mapsto t_2^{\prime}\mid\mu^{\prime}}{v_1\coloneq t_2\mid\mu\mapsto v_1 \coloneq t_2^{\prime} \mid\mu^{\prime}}$$
Again, as with the typing rules all other evaluation rules of the language need to be adjusted to correctly propagate $\mu$