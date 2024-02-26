*Ascription* or *type annotation* is a way to explicitly add a type to a term, usually written as $t\ \mathtt{ as }\ T$ meaning term $t$ has type $T$ ([[Simply Typed Lambda Calculus]]). 
Such a term is then typed with the rule 

$$ \frac{\Gamma \vdash t_1:T}{\Gamma \vdash t\ \mathtt{as}\ T : T}$$ 
If combined with [[Subtyping]], ascription splits into two kinds: *downcasting* and *upcasting*.
An upcast ascribes a term a supertype of its checked type while downcasting ascribes it a subtype.
When having downcasting, there are some design difficulties, because this sometimes needs to be checked during runtime, when type information might not be available.