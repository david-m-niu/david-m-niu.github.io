---
layout: post
title:  "Intuition on the Lebesgue-Radon-Nikodym Theorem"
author: "Yours Truly"
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

In my first blog post, I'll discuss the proof of the Lebesgue-Radon-Nikodym Theorem as given in Folland's *Real Analysis*.

To begin with, this is really the combination of the Radon-Nikodym theorem and Lebesgue's decomposition theorem. The former states: Let $\sigma$-finite $\nu$ and $\mu$ be signed and positive measures respectively on $(X,M)$ where $\nu$ is absolutely continuous with respect to $\mu$. There exists a finite valued measurable function $f$ on $X$ such that $\mu(E) = \int_E f d\mu$ for every measurable $E$, and $f$ is unique $\mu$-a.e. The latter theorem says that for any two $\sigma$-finite signed measures $\mu$ and $\nu$, we can decompose $\nu$ into the sum of two $\sigma$-finite signed measures $\nu_0$ and $\nu_1$ which are respectively absolutely continuous and singular with respect to $\mu$.

The proof can be reduced to the case where $\nu$ and $\mu$ are finite positive measures; this is because if they are $\sigma$-finite measures, then $X$ is a countable union of intersections of $\mu$- and $\nu$-finite sets, say $\{A_j\}$. Then, we can take $\mu_j(E) = \mu(E \cap A_j)$ and $\nu_j(E)$ similarly, which reduces to the case of finite positive measures, giving us $d\nu_j = d\lambda_j + f_j d\mu_j$ for each $j$, and then we simply take $\lambda = \sum \lambda_j$ and $f = \sum f_j$. Also, if $\nu$ is a signed measure


