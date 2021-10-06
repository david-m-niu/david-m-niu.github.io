---
layout: post
title:  "On the Dual Space of $L^p$"
author: "Yours Truly"
tags: [math, measure theory]
---

Today, I discuss the isometrical relation between $L^q$ and $(L^p)^\*$, where $p$ and $q$ are conjugate exponents.

Rather silly of me, but it goes without saying that if $p$ and $q$ are conjugate exponents, then $p,q \geq 1$ with the formal equality that $1^{-1} + \infty^{-1} = 1$. Also, we let $(L^p)^\*$ denote the set of bounded linear functionals from $L^p$ to $\mathbb{R}$ (or $\mathbb{C}$). Now given some $g \in L^p$, define a linear map $\phi_g(f) = \int fg$, which is bounded by H&ouml;lder's inequality, and here we arrive at the crux of today's discussion, for the map $g \rightarrow \phi_g$ is almost always an isometry from $L^q$ into $(L^p)^\*$.

<details>
	<summary>Firstly, if either $q$ is finite or $\mu$ is semifinite, then $\phi_g$ preserves length.</summary>
	&emsp;Particularly, $||g|| = ||\phi_g|| = \sup \{|\int fg|: ||f||_p = 1\}$, the last term of which is just the operator norm.
</details>
<details>
	<summary>Conversely, if the 'operator norm' restricted to the space of simple functions with $\mu$-finite support, denoted as $M_q(g)$, is finite and $g$ has $\sigma$-finite support or $\mu$ is semifinite, then $g \in L^q$ and $||g||_q = M_q(g)$.</summary>
	&emsp;Firstly, we remark that if $f$ is bounded and measurable with $\mu$-finite support and $||f||_p = 1$, then $|\int fg| \leq M_q(g)$; for instance, we can create sequence of simple functions convergent to $f$ and apply the dominated convergence theroem. Now there are three steps.
	<br/>
	&emsp;1. It is in fact enough to assume $\sigma$-finite support, since this holds when $\mu$ is semifinite. We can take an increasing sequence of sets with finite measure whose union is the support of $g$, as well as a sequence of simple functions $\{g_n\}$ with matching support which converges to $g$ pointwise.
</details>
<details>
	<summary>Finally, if $\phi \in (L^p)^*$ and $1 < p < \infty$ or $\mu$ is $\sigma$-finite, then there exists $g \in L^q$ such that $\phi(f) = \int fg$ for all $f \in L^p$, so $L^q$ is isometrically isomorphic to $(L^p)^*$.</summary>
	&emsp;This last one is a bit long.
</details>
<br/>
With this in mind, it is usual to say simply that $L^q$ is the dual Banach space of $L^p$, as per [Wikipedia](https://en.wikipedia.org/wiki/Lp_space#Dual_spaces).
