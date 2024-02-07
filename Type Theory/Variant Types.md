*Variant Types* are generalizations of [[Sum Types]], which allow combining terms of an arbitrary number of types ([[Type System]]), written as $\langle l=t\rangle$ with types $\langle l_1:\tau_1,\dots,l_n:\tau_n\rangle$.
A variant term is a value ([[Values and Normal Forms]]) when the inner term is a value.
Typing rules for variant terms are 

$$ \frac{\Gamma \vdash t:\tau}{\Gamma v\vdash \langle l=t\rangle : \langle l_1:\tau_1,\dots,l_k:\tau,\dots,l_n:\tau_n \rangle}$$
Since a term $\langle l=t\rangle$ can have any variant type including the label $l$, for a type system with unique types, this needs to be combined with [[Ascription]].
Evaluation ([[Evaluation Relation]]) of variant terms is done with

$$ \frac{t \mapsto t^{\prime}}{\langle l=t\rangle\mapsto \langle l=t^{\prime}\rangle}$$

### Optional Types

Combining variant types with the [[Unit Type]] gives optional types 
$$ \langle \mathtt{none} : \mathtt{Unit}, \mathtt{some}:\tau\rangle$$
A term of this type is either a trivial unit or some term of type $\tau$. This can be used for programs that should return something of type $\tau$, but can fail.

### Enumerations 

Only using $\mathtt{Unit}$ in a variant type gives the concept of an *enumeration*, where only the labels are relevant

$$ \langle \mathtt{mon}:\mathtt{Unit},\mathtt{tue}:\mathtt{Unit},\mathtt{wed}:\mathtt{Unit},\mathtt{thu}:\mathtt{Unit},\mathtt{fri}:\mathtt{Unit},\mathtt{sat}:\mathtt{Unit},\mathtt{sun}:\mathtt{Unit}\rangle$$ 
### Single value variants

A variant type $\langle l:\tau\rangle$ with only a single type $\tau$ can be used to "box" certain terms, that is give them labels to make sure they are only be used the way they are intended 
$$ \langle \mathtt{dollarAmount}:\mathtt{Int}\rangle$$
$$ \langle \mathtt{euroAmount}:\mathtt{Int}\rangle$$