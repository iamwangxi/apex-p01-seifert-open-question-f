# 4. An explicit unequal-genus pair

[Previous: connected sums](connected-sum.md) · [Next: the product-region obstruction](obstruction.md) · [Sources](../sources/bibliography.md)

Let $C$ be the right-handed trefoil and let $J=W_0^+(C)$ be its positive-clasp, zero-framing (untwisted) Whitehead double. Let $V=N(C)$ and $T_J=\partial V$. A zero-framed longitude of $V$ is the preferred longitude of $C$.

The standard genus-one Whitehead surface $Q$ is the plumbing of the zero-framed companion annulus with a clasp Hopf annulus. Move the companion annulus to an annulus $A_0\subset T_J$; the remainder is a pair of pants

$$
P\subset V\setminus\mathrm{Int}N(J),
\qquad
\partial P=\lambda_J\cup\lambda_+\cup\lambda_-,
$$

where $\lambda_\pm$ are oppositely oriented zero-framed longitudes on $T_J$. Before smoothing, $Q=P\cup A_0$; move and smooth it into the pattern side, away from $T_J$.

Let $F$ be the once-punctured-torus fibre of the trefoil. Take two disjoint parallel copies $F_+,F_-$ in $E(C)$ with opposite orientations and boundaries matching the two longitudinal boundaries of a parallel copy of $P$. Replace $A_0$ by these two copies and smooth the seams. Call the resulting one-boundary surface $H$:

$$H=P\cup F_+\cup F_-.$$

Its Euler characteristic is $-1-1-1=-3$, so $g(H)=2$, whereas $g(Q)=1$.

**Lemma 4.1 (the elementary pattern fact).** The zero-framing Whitehead pattern $W\subset V$ is not contained in a ball in $V$, and no meridian disc of $V$ is disjoint from $W$. Consequently the outer torus $T_J$ is incompressible in the pattern exterior $X=V\setminus\mathrm{Int}N(W)$, and $W$ does not bound an embedded disc in $V$.

**Pattern verification.** Cut $V$ along its usual meridian disc, which meets $W$ twice. The zero-winding Whitehead curve has a returning arc at either copy of the cut disc, and the two returning arcs form the Whitehead clasp. In the longitudinal infinite cyclic cover $D^2\times\mathbb R$, a lift of $W$ closes using returning arcs in two consecutive fundamental domains. Two consecutive closed lifts have linking number $+1$ or $-1$: the two crossings between their returning arcs have the same sign, and there are no other intercomponent crossings. The choice of clasp sign changes the sign, not nonvanishing.

If $W$ were contained in a ball in $V$, all its lifts would lie in disjoint lifted balls and every such linking number would be zero. If a meridian disc missed $W$, cutting along that disc would put $W$ in a ball, with the same contradiction. A compression of $T_J$ in $X\subset V$ has meridional boundary (the kernel of $\pi_1(T_J)\to\pi_1(V)$), so would supply such a meridian disc. Finally a disc bounded by $W$ has a ball neighbourhood in $V$, contradicting the first assertion. $\square$

**Lemma 4.2.** The pair of pants $P$ is incompressible in $X$ and is boundary-incompressible relative to $T_J$.

**Proof.** Every essential simple closed curve on a pair of pants is parallel to a boundary component. A curve parallel to $\lambda_+$ or $\lambda_-$ has nonzero class in $\pi_1(V)\cong\mathbb Z$, so cannot be the boundary of a compression disc in $X$. A compression along a curve parallel to $\lambda_J$ would, using the intervening annulus in $P$ and the boundary collar of $N(J)$, give an embedded disc bounded by the pattern $W$ in $V$. Lemma 4.1 excludes it.

For boundary-incompressibility, first note that $X$ is irreducible. A sphere in $X$ bounds a ball in the solid torus $V$. The connected pattern $W$, disjoint from that sphere, lies either inside or outside the ball. It cannot lie inside, by Lemma 4.1. Hence the ball misses $W$ and may be chosen to miss its tubular neighbourhood, so it is a ball in $X$.

Hatcher's Lemma 1.11, [H], p.20, says that an incompressible surface in an irreducible three-manifold, with boundary contained in torus boundary components, is either boundary-incompressible or a boundary-parallel annulus. The surface $P$ is a two-sided pair of pants, all of whose boundary components lie on the two boundary tori of $X$. It is not an annulus. The lemma therefore makes $P$ boundary-incompressible, in particular relative to $T_J$. $\square$

**Lemma 4.3.** The surfaces $Q$ and $H$ are incompressible Seifert surfaces of genera 1 and 2, respectively, and have disjoint representatives.

**Proof of incompressibility.** The trefoil fibre $F$ is an incompressible, boundary-incompressible once-punctured torus. For incompressibility, its exterior is the mapping torus of $F$, so the fibre subgroup injects; boundary-incompressibility also follows from the one-longitude knot-surface argument in [S], Lemma 4.2, pp.8–9. Thus the two companion-side pieces of $H$ have those properties.

The torus $T_J$ is incompressible on the pattern side by Lemma 4.1 and on the companion side because the trefoil is nontrivial. The amalgamated-product normal form shows that it remains incompressible after gluing. Hence $E(J)$ contains a $\mathbb Z^2$ subgroup and cannot be the solid-torus exterior of an unknot. In particular $J$ is nontrivial. The displayed genus-one surface $Q$ is therefore of minimum possible genus and is incompressible.

For $H$, use the standard disc proof of gluing incompressible, relatively boundary-incompressible pieces across an incompressible torus. To spell it out, put a proposed compression disc transverse to $T_J$ with minimum intersections. Remove innermost circle intersections using incompressibility of $T_J$ and irreducibility of the knot exterior. An outermost remaining arc gives a boundary compression of either $P$ or a copy of $F$ relative to $T_J$. Their boundary-incompressibility says its surface arc is boundary-parallel; the disc it cuts off permits a disc exchange removing that intersection arc. Repeat. The compression disc would eventually lie on one side of $T_J$, contradicting incompressibility of $P$ or $F$. Thus $H$ is incompressible. All seams can be rounded and the true boundary collars made neat.

**Proof of disjointness.** In the unsmoothed model $Q=P\cup A_0$, the annulus $A_0$ is incident to the same normal side of $P$ at both longitudinal ends. This follows either from the oriented plumbing or from the opposite induced orientations of $\lambda_+$ and $\lambda_-$. Push a copy of $P$ into the other normal side, and let its two longitudinal boundaries remain on $T_J$, just outside $A_0$. At either seam take local coordinates $(s,x,r)$ with $r\ge0$ pointing into $X$, $P=\{x=0\}$, and $A_0=\{r=0,x\ge0\}$. The copy of $P$ has $x<0$, while the rounded and pushed-in $Q$ lies in $x\ge0$ near that seam. The same side choice works at both ends. The two parallel copies of $F$ attach on the companion side of $T_J$, where $Q$ is absent. Small parallel boundary longitudes at $\partial E(J)$ finish an everywhere disjoint realization. No tubing handle is added to the standard surface: $H$ is the annulus *replacement* described above, and its incompressibility comes from the piecewise disc argument. $\square$
