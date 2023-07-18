Let $\Lambda$ be a [[Lattice]] in $\mathbb{C}$ with basis $1,\tau$ where $\tau\in\mathbb{C}\setminus \mathbb{R}$ ([[Complex numbers]],[[Real Numbers]]).
Then Weierstrass $\wp$-function for $\Lambda$ is defined as 
$$ \wp(z) = \frac{1}{z^2} + \sum_{\omega \in \Lambda^{\prime}} (\frac{1}{(z-\omega)^2} - \frac{1}{\omega^2})$$ 
where $\Lambda^{\prime} = \Lambda \setminus \{0\}$.
This series converges for all $z\notin \Lambda$, so it is a [[Meromorphic Function]], and is a [[Elliptic Function]].
Its derivative is $\wp^{\prime}(z)$ is also an elliptic function and given by 
$$ \wp^{\prime}(z) = \sum_{\omega\in\Lambda} \frac{-2}{(z-\omega)^3}$$ 
$\wp$ and $\wp^{\prime}$ satisfy the following 

$$(\wp^{\prime})^2 = 4 \wp^3 - g_2\wp - g_3$$ 
where 
$$ g_2 = 60\sum_{\omega \in \Lambda^{\prime}} \frac{1}{\omega^4} \quad g_3 = 140 \sum_{\omega\in\Lambda^{\prime}} \frac{1}{\omega^6}$$ 