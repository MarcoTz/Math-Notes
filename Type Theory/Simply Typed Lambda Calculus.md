The *simply typed lambda calculus* extends the [[Untyped Lambda Calculus]] by adding a type system.
Types are given by the following grammar:

$$ T \Coloneqq \mathtt{Bool} \mid T\rightarrow T$$ Where $\mathtt{Bool}$ can also be replaced with any other primitive type ([[Base Types]]).
We need at least one such type, otherwise the type system is degenerate.

Typing is then done with an environment $\Gamma$ containing a list of variables $x$ with their corresponding type $\tau$, written $x:\tau \in \Gamma$.
Typing a term $t$ with type $\tau$ using an environment $\Gamma$ is written $\Gamma \vdash t:\tau$, and done using the following rules

 $$ \frac{\Gamma,x:T_1\vdash t_2:T_2}{\Gamma\vdash\lambda x:T_1.t_2:T_1\rightarrow T_2}$$ $$\frac{x:T\in\Gamma}{\Gamma\vdash x:T}$$ 
 $$ \frac{\Gamma\vdash t_1:T_{11}\rightarrow T_{12}\quad \Gamma \vdash t_2:T_{11}}{\Gamma\vdash t_1\ t_2 : T_{12}}$$ In the rule for lambda abstractions, the type of $x$ is annotated in order to make sure this has a unique type. If we leave the annotation out, $x$ can be any type (but that might make the body untypable depending on which type is chosen).
This system has type safety ([[Type Safety]]) assuming the base types on their own are.