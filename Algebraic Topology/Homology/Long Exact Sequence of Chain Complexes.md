Given [[Chain Complexes]] $A_n$, $B_n$ and $C_n$ and maps $i:A_n\rightarrow B_n$ and $j:B_n\rightarrow C_n$ for all $n$ s.t. the following sequence is exact ([[Exact Sequence]]) 

$$ 0 \rightarrow A_n \xrightarrow{i} B_n \xrightarrow{j} C_n$$
we get a *short exact sequence of chain complexes* seen in the following diagram

$$\begin{array}{}
&& 0 && 0 && 0 \\
& & \downarrow & & \downarrow && \downarrow \\
\dots & \rightarrow & A_{n+1} & \xrightarrow{\partial} & A_n & \xrightarrow{\partial} & A_{n-1} & \rightarrow & \dots \\
& & \downarrow \small{i} & & \downarrow \small{i} & & \downarrow \small{i} \\
\dots & \rightarrow & B_{n+1} & \xrightarrow{\partial} & B_n & \xrightarrow{\partial} & B_{n-1} & \rightarrow & \dots
\\
& & \downarrow \small{j} & & \downarrow \small{j} & & \downarrow \small{j} \\
\dots & \rightarrow & C_{n+1} & \xrightarrow{\partial} & C_n & \xrightarrow{\partial} & C_{n-1} & \rightarrow & \dots\\
& & \downarrow & & \downarrow && \downarrow \\
&& 0 && 0 && 0 
\end{array} $$

This sequence gives us a long exact sequence of  [[Homology]] groups

$$ \dots \rightarrow H_n(A) \xrightarrow{i_*} H_n(B) \xrightarrow{j_*} H_n(C) \xrightarrow{\partial} H_{n-1}(A) \xrightarrow{i_*} H_{n-1}(B) \xrightarrow{j_*} H_{n-1}(C) \rightarrow \dots $$
