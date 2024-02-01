The *Untyped Lambda Calculus* is defined by the following grammar 

$$ t \Coloneqq x \mid \lambda x.t \mid t_1\ t_2$$

Where $x$ comes from a fixed set of variables $x,y,\dots$. 
A variable $x$ is called *bound* if it appears in a term $t$ inside a lambda abstraction $\lambda x.t$, otherwise it is called *free*. 
In this case $\lambda x.$ is called the *binder* of $x$.
A term with no free variables is called *closed* or a *combinator*.

The untyped lambda calculus is evaluated using the rule 
$$ (\lambda x.t_1)\ t_2 \mapsto t_1[t_2/x]$$ where $t_1[t_2/x]$ means replacing (free) $x$ in $t_1$ for $t_2$. 
A term $(\lambda x.t_1)\ t_2$ is called a *redex* (reducible expression).

### Substitution
When reducing a redex (with any evaluation order ([[Evaluation Orders in Lambda Calculus]])), substitution is defined as follows 
$$ x[s/x] = s$$
$$ y[s/x] = y\quad \text{ if }y\neq x$$
$$ (\lambda y.t_1)[s/x]= \lambda y. t_1[s/x]\quad \text{if }y\neq x$$ 
$$ (t_1\ t_2)[s/x] = t_1[s/x]\ t_2[s/x]$$
 When  substitution, we always assume all variables are distinct. 
If we have a substitution $\lambda x.t[s/x]$, we always have to rename the bound $x$ to a new variable before we can substitute. 
This is called $\alpha$-renaming, and terms that are equal up to $\alpha$-renaming are called *$\alpha$-equivalent*.
### Programming in Lambda Calculus

#### Booleans
$tru = \lambda t.\lambda f. t$ $fls = \lambda t.\lambda f.f$ 
$if = \lambda l.\lambda m.\lambda n. l\ m\ n$ 
$and = \lambda b \lambda c. b c fls$ 

#### Pairs
$pair = \lambda f.\lambda s.\lambda b.b\ f\ s$
$fst = \lambda p. p\ tru$ 
$snd = \lambda p\ fls$ 

#### Chuch Numerals 
$zero = \lambda s.\lambda z. z$ 
$one = \lambda s.\lambda z. s\ z$ 
$two = \lambda s.\lambda z. s\ s\ z$
$three = \lambda s.\lambda z. s\ s\ s\ z$ 
$\vdots$ 
$succ = \lambda n.\lambda s.\lambda z. s\ (n\ s\ z)$ 
$plus = \lambda m.\lambda n.\lambda z. m\ s\ (n\ s\ z)$ 
$times = \lambda m.\lambda n. (plus\ n)\ zero$ 
$iszero  = \lambda m. m\ (\lambda x. fls)\ tru$

$zz = pair\ zero\ zero$
$ss=\lambda p.pair\ (snd\ p)\ (plus\ one\ (snd\ p))$
$prd = \lambda m.fst\ (m\ ss\ zz)$ 