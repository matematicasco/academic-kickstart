+++
title = "Lagrangian-Eulerian Approach for Nonlocal Conservation Laws"
date = "2022-07-25"
authors = ["Abreu, E.", "delacruz-r","juajibioy-j", "Lambert, W."]
publication_types = ["2"]
publication = "*Journal of Dynamics and Differential Equations*. doi:10.1007/s10884-022-10193-8"
abstract = "In this work, we construct and analyze a new fully discrete Lagrangian-Eulerian numerical method for  the treatment of dynamics of conservation laws with nonlocal flux and influence of the source term in the solution. The scheme is based on the improved concept of no-flow curves. We use the recent results of S. Blandin & P. Goatin (2016), [Numer. Math. 132, 217-241], to obtain a $BV$ estimate for the new fully discrete (explicit) Lagrangian-Eulerian scheme with a rigorous analysis to prove its convergence for the entropic solution. We also derive a weak CFL-type stability condition that does not require the derivative of the nonlocal flux as is the case for classical schemes. As an application of the proposed approach, we present a combined analytical-numerical study on the interplay between local and nonlocal conservation laws motivated by dynamics of differential equations such as traffic flow and related problems. For a suitable exponential kernel $\omega_\eta$ of class $C^2$, we present theoretical and numerical evidence that the limit of solutions to the nonlocal equation coincides with the unique entropy-admissible solution of the scalar conservation law $\rho_t + (\rho^m v(q))_x = 0$. It should be emphasized that hypotheses on the solution were verified numerically only. In this regard, the flux function $f(\rho)=\rho^m v(q)$ satisfies $q(x,t)=\int_x^{x+\eta} \omega_\eta(x-y)\rho(y,t)dy$, for an integer $1\leq m$, where $\omega_\eta$ is unitary (integral equals to 1) and non-increasing kernel such that $\omega_\eta(s)=\frac{1}{(1-e^{-1/\eta^2})\eta^2} e^{-s/\eta^2}$ for every $s\in\mathbb{R}$. It turns out that we also use recent results of A. Bressan & W. Shen (2020), [Arch. Rational Mech. Anal., 237, 1213-1236] and A. Bressan & W. Shen (2021), [Communications in Mathematical Sciences 19(5) 1447 - 1450], as foundations of the Lagrangian-Eulerian approach for nonlocal conservation laws."
selected = false
projects = ["gedmys"]
tags =["Partial Differential Equations","GEDMyS","Cat. A1"]
doi = "10.1007/s10884-022-10193-8"
math = true
highlight = true
+++

