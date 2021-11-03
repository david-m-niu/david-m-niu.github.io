---
layout: default
---

## Notes | Where Is My Intuition?

When a concept isn't painfully obvious, it's simply painful. Pain sucks.

### 3 October 2021

#### Variance

The variance $\sigma^2(X)$ of a random variable $X$ is simply defined as $\sigma^2(X) = E(X-E(X)^2)$. This then is a measure of how much $X$ deviates from its mean $E(X)$. Note that we take the average squared difference because taking simply the average difference $E(X-E(X))$ gives 0 by linearity, whereas the absolute value function is not differentiable at 0.

#### Taking the $\lim \sup$ of Sequences of Sets

Let $X_n$ be a sequence of subsets of $X$. On one hand, we know that $\lim \sup X_n$ consists of elements belonging to $X_n$ for infinitely many $n$, but we also rigorously define $\lim \sup X_n = \bigcap_{n=1}^{\infty} \left(\bigcup_{m=n}^{\infty} X_m\right)$. We now derive the intuition by unifying these two definitions. If $x$ is in infinitely many $X_n$, then for arbitrary $n$ we see that $x \in \bigcup_{m=n}^{\infty} X_m$, and thus $x$ is clearly in the intersection of these unions. However, if $x$ is only in finitely many $X_n$, we can simply pick some $N \geq n$, in which case $x \not\in \bigcup_{m=N}^{\infty} X_m$, and then $x$ is not in our intersection of unions either.
