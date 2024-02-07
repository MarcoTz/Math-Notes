The *Untyped Lambda Calculus* is defined by the following grammar 

$$ t \Coloneqq x \mid \lambda x.t \mid t_1\ t_2$$

Where $x$ comes from a fixed set of variables $x,y,\dots$. 
A variable $x$ is called *bound* if it appears in a term $t$ inside a lambda abstraction $\lambda x.t$, otherwise it is called *free*. 
In this case $\lambda x.$ is called the *binder* of $x$.
A term with no free variables is called *closed* or a *combinator*.

The untyped lambda calculus is evaluated ([[Evaluation Relation]]) using the rule 
$$ (\lambda x.t_1)\ t_2 \mapsto t_1[t_2/x]$$ ([[Substitution]]) 
A term $(\lambda x.t_1)\ t_2$ is called a *redex* (reducible expression).

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