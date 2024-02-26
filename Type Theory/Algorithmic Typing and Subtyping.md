In some [[Type System]]s, especially with [[Subtyping]], there are rules that are nondeterministic, for example transitivity in subtyping:

$$ \frac{\tau<:\sigma\quad \sigma<:\gamma}{\tau<:\gamma}$$ To get an algorithm for typing/subtyping, such rules are eliminated and replaced by deterministic ones. For example, reflexivity can usually be inferred from other rules and be removed.
The most problematic rule is usually the subtyping rule, as it can be applied at any time

$$ \frac{\tau<:\sigma \quad \Gamma \vdash t:\sigma}{\Gamma \vdash t:\tau}$$ 
This is removed by identifying where subtyping is actually needed (for example applications) and modify that typing rule to allow subtyping.
