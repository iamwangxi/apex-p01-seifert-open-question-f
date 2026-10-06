# 3. Connected sums: two elementary facts

[Previous: atoroidal exteriors](atoroidal.md) · [Next: the Whitehead pair](whitehead-pair.md) · [Sources](../sources/bibliography.md)

Let $K_1\#K_2$ be formed using a decomposing meridional annulus $A$ in its exterior. Cutting along $A$ gives the two summand exteriors, with the usual boundary collars. Write $F_1\mathbin{\natural}F_2$ for the surface obtained by joining two Seifert surfaces along one spanning arc of $A$.

**Lemma 3.1.** If $F_i$ are incompressible Seifert surfaces for $K_i$, then $F_1\mathbin{\natural}F_2$ is an incompressible Seifert surface for $K_1\#K_2$, of genus $g(F_1)+g(F_2)$.

**Proof.** The surface is connected and orientable and has one longitude boundary; gluing along an interval gives

$$
\chi(F_1\mathbin{\natural}F_2)=\chi(F_1)+\chi(F_2)-1.
$$

Choose basepoints in the joining interval. Van Kampen gives

$$
\pi_1(E(K_1\#K_2))=G_1*_{\langle\mu\rangle}G_2,
\qquad
\pi_1(F_1\mathbin{\natural}F_2)=\pi_1(F_1)*\pi_1(F_2),
$$

where $G_i=\pi_1(E(K_i))$ and the meridians of the factors are identified. By the Loop Theorem, each incompressible, two-sided $F_i$ is $\pi_1$-injective; see [H], Corollary 3.3, p.59. For a disc the group is trivial. Hence we may put $H_i=\pi_1(F_i)\subseteq G_i$. The linking homomorphism $G_i\to\mathbb Z$ vanishes on $H_i$: a loop on a Seifert surface can be pushed normally off that surface, giving algebraic intersection zero. It is injective on the meridian subgroup. Thus

$$H_i\cap\langle\mu\rangle=\{1\}.$$

The normal-form theorem for an amalgamated free product now shows that every nonempty reduced word alternating between nonidentity elements of $H_1$ and $H_2$ remains nontrivial in the exterior group. The surface inclusion is injective, so an essential simple closed curve on it cannot bound a compression disc in the exterior. The Euler characteristic formula proves the genus assertion. Each sum is also boundary-incompressible by the one-longitude argument of [S], Lemma 4.2, pp.8–9. The latter property is used separately when applying the product-region criterion below. $\square$

**Lemma 3.2.** If $F_i$ and $G_i$ have disjoint representatives in each summand, then $F_1\mathbin{\natural}F_2$ and $G_1\mathbin{\natural}G_2$ have disjoint representatives, with consistently chosen joining bands.

**Proof.** Arrange the two boundary longitudes in each summand to be parallel and distinct, and arrange the decomposing annulus to meet the surfaces in two disjoint spanning arcs. Glue the corresponding arcs in matching order. All other parts are already disjoint. Boundary-collar adjustments do not change the ambient isotopy classes, since boundary longitudes are allowed to move. The choices can be made once when a torus-twist family agrees outside its twisting collar. $\square$
