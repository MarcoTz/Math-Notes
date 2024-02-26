In a [[Type System]] with [[Subtyping]], let $\tau$ and $\sigma$ be two types. Then we define 

* The *join* of $\tau$ and $\sigma$, written $\tau \vee \sigma = \gamma$ is defined as $\tau,<:\gamma$ , $\sigma<:\gamma$ and for all $\gamma^{\prime}$ with $\tau<: \gamma^{\prime}$ and $\sigma <: \gamma^{\prime}$ we have $\gamma <: \gamma^{\prime}$ 
* The *meet* of $\tau$ and $\sigma$, written $\tau \wedge \sigma = \gamma$ is defined as $\gamma <: \tau$, $\gamma<:\sigma$ and for all $\gamma^{\prime}$ with $\gamma^{\prime}<:\tau$ and $\gamma^{\prime}<:\sigma$ we have $\gamma^{\prime}<:\gamma$.
* A system is said to have joins/meets if for any pair $\tau,\sigma$, $\tau \vee \sigma$ / $\tau\wedge \sigma$ exists

A slightly weaker property of a subtyping system is the existance of *bounded joins and meets* 
* $\tau$ and $\sigma$ are said to be *bounded below* if there is some $\gamma <: \tau$ and $\gamma <: \sigma$
* $\tau$ and $\sigma$ are said to be *bounded above* if there is some $\tau<:\gamma$ and $\sigma<:\gamma$
* A system is said to have bounded joins/meets if whenever $\tau$ and $\sigma$ are bounded above/blow, $\tau\vee \sigma$/$\tau\wedge\sigma$ exists 