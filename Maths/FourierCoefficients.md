----
author: Arthur Van Loo
description: based on https://www.youtube.com/watch?v=ijQaTAT3kOg&t=225s
----

# Fourier coefficients

- setting up intervals of 2 trigonometric functions

# Determine coefficients

## multiply by $sin(mt)$

$\implies$ $a_0 \cdot sn(mt)$ always zero

- same for $cos(nt)$
- only not zero when n = m
$\implies$ integral = $b_m\pi$
$\implies$ $b_m = \frac{1}{\pi} \int_0^(2\pi)f(t)sin(mt)dt$


## Multiply by cos(mt)

- integral = $a_m \pi$

## Multiply by 1

- $\pi a_0$ = integral

# Convergence

- f & f' piecewies continuous on [-L, L)

$$$
\frac{a_0}{2} + \sum_{n=1}^{\infty} a_n cos(\frac{n\pi t}{L}) + \sum_{n=1}^\infty b_n sin(\frac{n\pi t}{L})
$$$
