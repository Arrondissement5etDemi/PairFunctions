# PairFunctions

This document collects known realizable analytical forms of pair correlation functions $g_2(r)$ and structure factors $S(k)$ for disordered many-body systems.

## $d$-Dimensional Ground-State Free Fermi gases
$$
g_2(r) = 2^d\Gamma(1 + d/2)^2\frac{J_{d/2}^2(k_Fr)}{(k_Fr)^d},
$$

where $J_\nu(x)$ is the Bessel J function of order $\nu$, and $k_F$ is the Fermi sphere radius.

$$
S(k) = 1 - \alpha_2(k, k_F),
$$

where $\alpha_2(k, k_F)$ is the intersection volume of two $d$-dimensional spheres of radius $K_F$ separated by a distance $k$, divided by the volume of the sphere with radius $K_F$.

### $S(k)$ for $k < 2k_F$ in the first three dimensions

$d$|$S(k)$|
---|---|
1|$q/2$|
2|$\frac{2}{\pi}\left(\arcsin\frac{q}{2} + \frac{q}{2}\sqrt{1-\frac{q^2}{4}}\right)$|
3|$\frac{3 q}{4} + \frac{q^3}{16}$

where $q = k/k_F$. $S(k) = 1$ for $k \geq 2 k_F$.

Reference: 
- R. P. Feynman, Statistical Mechanics (Westview Press, Boulder, Colorado, 1998).
- S. Torquato, A. Scardicchio, and C. E. Zachary, “Point processes in arbitrary dimension from Fermionic gases, random matrix theory, and number theory,” [J. Stat. Mech.: Theory Exp. 2008, P11019](https://www.scopus.com/record/display.uri?eid=2-s2.0-65549094121&origin=inward) (2008).

## 2D Ginibre ensemble
