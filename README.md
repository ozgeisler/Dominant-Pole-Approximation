# Dominant Poles Approximation (3rd-order → 2nd-order)

This project investigates the **dominant poles** concept by approximating a third-order system with a second-order system and comparing time-domain performance metrics.

## Systems
Full system:
\[
G(s)=\frac{s+2}{(s+1+3i)(s+1-3i)\left(\frac{1}{p_3}s+1\right)}
\]

Approximation (neglect the third pole):
\[
\tilde{G}(s)=\frac{s+2}{(s+1+3i)(s+1-3i)}
\]

## Performance metrics (computed from time response)
- Percent Overshoot
- Settling Time (within 4%)
- Rise Time (10% → 80%)

