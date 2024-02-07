There is a correspondence between types and natural logic, called the *Curry-Howard correspondence*.
Usually this is stated between natural deduction ([[Natural Deduction Systems]]) with classical logic and [[Simply Typed Lambda Calculus]], but it also holds for other languages.
This particular correspondence has the following form

| Logic | Programming Languages |
| ---- | ---- |
| Propositions | Types |
| $P\supset Q$ | $P\rightarrow Q$ |
| $P\wedge Q$ | $P\times Q$ |
| Proof of $P$ | term $t$ of type $P$ |
| $P$ is provable | there is some term $t$ of type $P$ |
