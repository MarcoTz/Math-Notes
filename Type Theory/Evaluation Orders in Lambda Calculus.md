Let $t$ be a term in a lambda calculus (for example [[Untyped Lambda Calculus]]). 
Then there are several ways to choose how redexes in $t$ are reduced 
* Full $\beta$ reduction: Any redex can be reduced in any time, order is not relevant
* Normal Order: Only the leftmost, outermost redex can be reduced at any step
* Call By Name: Normal Order, but no redexes inside lambda abstractions are reduced
* Call By Need: Call By Name, but whenever an argument is reduced, all occurrences of the argument are immediately replaced by the result. This requires a graph representation of $t$
* Call By Value: Like Normal Order, but Arguments always have to be fully evaluated before the application can be reduced