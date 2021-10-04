---
layout: post
title:  "Intuition on the Lebesgue-Radon-Nikodym Theorem"
author: "Yours Truly"
tags: [math, measure theory]
---

In my first blog post, I discuss the proof of the Lebesgue-Radon-Nikodym Theorem as given in Folland's *Real Analysis*.

To begin with, this is really the combination of the Radon-Nikodym theorem and Lebesgue's decomposition theorem. Radon-Nikodym states: let $\sigma$-finite $\nu$ and $\mu$ be signed and positive measures respectively on $(X,M)$ where $\nu$ is absolutely continuous with respect to $\mu$. Then, there exists a finite valued measurable function $f$ on $X$ such that $\mu(E) = \int_E f d\mu$ for every measurable $E$, and $f$ is unique $\mu$-a.e. On the other hand, Lebesgue decomposition says that for any two $\sigma$-finite signed measures $\mu$ and $\nu$, we can decompose $\nu$ into the sum of two $\sigma$-finite signed measures $\nu_0$ and $\nu_1$ which are respectively absolutely continuous and singular with respect to $\mu$.

The proof can be reduced to the case where $\nu$ and $\mu$ are finite positive measures; this is because if they are $\sigma$-finite measures, then $X$ is a countable union of intersections of $\mu$- and $\nu$-finite sets, say $\{A_j\}$. Then, we can take $\mu_j(E) = \mu(E \cap A_j)$ and $\nu_j(E)$ similarly, which reduces to the case of finite positive measures, giving us $d\nu_j = d\lambda_j + f_j d\mu_j$ for each $j$, and then we simply take $\lambda = \sum \lambda_j$ and $f = \sum f_j$. Also, if $\nu$ is a signed measure, we simply apply the previous case to $\nu^+$ and $\mu^-$ and subtract the results.

Having said that, we begin the proof for the case of finite positive measures by choosing $f$ as the 'supremum' of functions whose integrals with respect to $\mu$ are bounded by $\nu$. Then, the measure $d\lambda = d\nu - f d\mu$ is singular with respect to $\mu$, or else the maximality of $\int f d\mu$ is contradicted. Also, if $\{\nu_j\}$ is a sequence of positive measures, then 'additivity' holds for singularity and absolute continuity with respect to some $\mu$ (this was left as an exercise in Folland) which allows us to prove uniqueness $\mu$-a.e.
