Let $(A_n)$ and $(B_n)$ be inverse systems ([[Inverse Limit]]). A *homomorphism of inverse systems* $(A)_n\rightarrow (B_n)$ is a collection of homomorphisms $f_n:A_n\rightarrow B_n$ for each $n$ s.t. for $n^{\prime}\geq n$ the following [[Diagram]] commutes 

![[Inverse system homomorphism.png]]

A sequence $0\rightarrow (A_n) \rightarrow (B_n) \rightarrow (C_n) \rightarrow 0$ of homomorphisms of inverse systems is *exact* ([[Exact Sequence]]) if the corresponding sequences $0\rightarrow A_n \rightarrow B_n \rightarrow C_n \rightarrow 0$ are exact for all $n$. For such an exact sequence, the corresponding sequence $0\rightarrow \underleftarrow{\lim} A_n \rightarrow \underleftarrow{\lim} B_n \rightarrow \underleftarrow{\lim} C_n$ is also exact (the last map is not always surjecive).