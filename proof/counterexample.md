# 6. The counterexample and its checklist

[Previous: the product-region obstruction](obstruction.md) · [Next: a prime counterexample](prime.md) · [Sources](../sources/bibliography.md)

Let $C=3_1$ be the right-handed trefoil, let $J=W_0^+(C)$ be its positive-clasp, zero-framing Whitehead double, and let $B$ be the knot $K_\alpha$ of Banks's Figure 1, p.3. Use the surfaces and twist constructed in [§4](whitehead-pair.md) and [§5](obstruction.md). Set

$$
K=B\#W_0^+(C),\qquad
v=[R\mathbin{\natural}H],\qquad
u_n=[R_n\mathbin{\natural}Q]\quad(n\in\mathbb Z).
$$

**Theorem 6.1.** The vertex $v$ of $IS(K)$ has infinitely many pairwise distinct neighbours $u_n$ of strictly smaller genus. Hence (F) fails for knots in general.

**Proof.** Banks's Theorem 2.3, pp.3–5, supplies the incompressible genus-one surfaces $R,R_n$. Lemma 4.3 supplies the incompressible surfaces $Q,H$, of genera 1 and 2. By Lemma 3.1 all the displayed connected sums are vertices, and

$$
g(v)=1+2=3,\qquad g(u_n)=1+1=2.
$$

Choose the joining bands using disjoint representatives of $(R,R_0)$ and $(H,Q)$, with distinct parallel longitudes and the boundary-order matching of Lemma 3.2. Their sums are disjoint. The twist $\Psi$ fixes $R$, the entire second summand, and the joining bands. Consequently the **same fixed representative** $R\mathbin{\natural}H$ is disjoint from $R_n\mathbin{\natural}Q$ for every $n$.

Lemma 5.1 with $F=Q$ proves that the $u_n$ remain pairwise distinct after the connected sum. Each differs from $v$ by genus. Thus there are infinitely many distinct adjacent vertices of smaller genus. Whatever their relative areas are,

$$
c(u_n)<c(v),
$$

because the first coordinates satisfy $2<3$. This directly refutes (F). $\square$

## Construction checklist

| Required property | Reason |
|---|---|
| Specified first factor | Banks's Theorem 2.3 and Figure 1 fix the twisted Whitehead double $B$ |
| Specified second factor | $W_0^+(3_1)$ uses the right-handed trefoil, its preferred zero framing, and the positive Whitehead clasp |
| Genus-one surface $Q$ | The standard Whitehead surface $P\cup A_0$; Lemma 4.3 proves its incompressibility |
| Genus-two surface $H$ | Replace $A_0$ by two oppositely oriented parallel trefoil fibres; Lemmas 4.2–4.3 prove incompressibility |
| Disjoint $Q,H$ | The pair of pants is pushed to the normal side opposite the sealing annulus, then attached on the companion side |
| All sums incompressible | Lemma 3.1, using the Loop Theorem and amalgamated-product normal form |
| A fixed centre disjoint from the whole family | Lemma 3.2 and the twist's fixing the centre and joining bands |
| Pairwise distinct neighbours after summing | Lemma 5.1 transports the product-region obstruction |
| Strict genus decrease | $3>2$; area values and tie-breaking play no role |

There is no unspecified intermediate vertex or chosen path in $IS(J)$. The genus-two surface is an annulus replacement, whose incompressibility is proved separately; it is not obtained by adding an arbitrary tube to a minimum-genus surface.

The [prime Whitehead satellite construction, Theorem 7.1](prime.md), doubles these surfaces to give a prime counterexample with a genus-six vertex and infinitely many distinct genus-four neighbours.
