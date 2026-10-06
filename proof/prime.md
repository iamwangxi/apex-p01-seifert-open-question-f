# 7. A prime Whitehead satellite counterexample to (F)

[Previous: the composite counterexample](counterexample.md) · [Next: scope](scope.md) · [Sources](../sources/bibliography.md)

## 7.1. Construction and conclusion

The conventions for $`IS(K)`$ are ambient isotopy in the knot exterior, with boundary longitudes allowed to move on the boundary torus. Vertices are connected, orientable, incompressible Seifert surfaces. The aim is infinitely many distinct neighbours of strictly smaller genus, which implies failure of the lexicographic descending-link condition (F) independently of area.

Let $`C=3_1`$ be the right-handed trefoil. Let $`B`$ be the twisted Whitehead double $`K_\alpha`$ of the trefoil shown in Banks's Figure 1, p.3; the figure fixes the knot without a separate framing convention. Put

```math
J=W_0^+(C),\qquad K_0=B\#J,\qquad K'=W_0^+(K_0).
```

For the companion $`K_0`$, use the already proved surfaces

```math
V=R\natural H,\qquad U_n=R_n\natural Q,\qquad R_n=\Psi^n(R_0).
```

Here $`R`$ is the genus-one surface of Banks Figure 1. Banks's $`R_0`$ replaces the companion-torus annulus of $`R`$ by the frontier annulus of the trefoil's embedded Möbius band; $`\Psi`$ is Banks's meridional torus twist. In $`J`$, $`Q`$ is the standard genus-one zero-framed Whitehead surface, and $`H`$ replaces its companion annulus by two oppositely oriented parallel copies of the trefoil fibre, using the Whitehead pair of pants. This specifies $`H`$ as an annulus replacement, not as an arbitrary added tube. Both $`B`$ and $`J`$ are nontrivial: for $`B`$ this is part of Banks's genus-one construction and incompressible companion torus; for $`J`$ it is [Lemma 4.3](whitehead-pair.md).

By [Lemmas 3.1–3.2](connected-sum.md), [Lemma 5.1](obstruction.md), and [Theorem 6.1](counterexample.md), they have genera $`3`$ and $`2`$, respectively, are incompressible, and the $`U_n`$ are pairwise nonisotopic, with a representative of $`V`$ disjoint from every $`U_n`$. The twist $`\Psi`$ fixes $`V`$ and a collar of $`\partial E(K_0)`$.

For a Seifert surface $`F`$ in $`E(K_0)`$, form a surface $`D(F)`$ for $`K'`$ as follows. In the zero-framed Whitehead pattern exterior $`X`$, let $`P`$ be the standard pair of pants with one boundary longitude of $`K'`$ and two oppositely oriented preferred longitudes on the companion torus $`T`$. Attach two parallel copies $`F_+,F_-`$, with opposite orientations, to those two outer boundaries. Thus

```math
D(F)=P\cup F_+\cup F_-.
```

Different parallel choices of $`P`$ will be specified when disjointness is needed; no assertion that all arbitrary choices define a canonical operation is required. All $`D(U_n)`$ use a single fixed pattern piece and are obtained from $`D(U_0)`$ by the extended twist.

The vertex and neighbours are

```math
v'=[D(V)],\qquad u'_n=[D(U_n)],\qquad n\in\mathbb Z.
```

**Theorem 7.1 (Theorem C′).** The knot $`K'`$ is prime, and $`v'`$ has infinitely many pairwise distinct genus-four neighbours $`u'_n`$, while $`g(v')=6`$. Consequently (F) fails for a prime knot.

The proof occupies §§7.3–7.6, with its final assembly in §7.7.

## 7.2. Dependencies and theorem boundary

The companion construction is proved in this repository: [Lemmas 3.1–3.2](connected-sum.md), [Lemmas 4.1–4.3](whitehead-pair.md), [Lemma 5.1](obstruction.md), and [Theorem 6.1](counterexample.md). In particular, companion nonisotopy is used only after its connected-sum proof, rather than inferred from nonisotopy in the first factor alone.

The external sources and inspected editions are listed in the [bibliography](../sources/bibliography.md). Banks's Theorem 2.3, pp.3–5, specifies the knot and twist family. Hatcher's Lemmas 1.10–1.11, printed pp.19–20, Corollary 3.3, printed p.59, and Corollary 3.9, printed p.63, supply the solid-torus, boundary-incompressibility, Loop Theorem and asphericity facts used below. Farb–Margalit's Theorem 8.8, printed p.234, is the punctured Dehn–Nielsen–Baer theorem preserving puncture peripheral conjugacy classes. To obtain the one-boundary version, truncate a small neighbourhood of the puncture end and adjust the homeomorphism in the resulting boundary collar.

Besides amalgamated-product normal forms and basic Bass–Serre theory, the first proof of primality uses **Schubert's additivity of Seifert genus under connected sum** as a standard external theorem. Its original publication has not been independently inspected; no original theorem number or page is asserted. The second proof of primality does not depend on additivity.

We also use **Waldhausen's homotopy-to-isotopy theorem for two-sided incompressible surfaces** in the following standard form: two connected, properly embedded, two-sided, incompressible, boundary-incompressible surfaces in a compact orientable irreducible boundary-irreducible three-manifold, whose parametrizations agree on the boundary and are homotopic through proper maps relative to it, have ambient-isotopic images. The surfaces used here have negative Euler characteristic and essential boundary, and the manifold is sufficiently large. Section 7.6 reduces to precisely this form after an allowed boundary-collar isotopy. Waldhausen's original article, *On irreducible 3-manifolds which are sufficiently large*, *Annals of Mathematics* **87** (1968), 56–88, has not been independently inspected. Kakimizu 1992, pp.235–236, applies the corresponding homotopy/product machinery, but that application is not a verbatim verification of this standard corollary. No missing Kakimizu 1991 result is used.

## 7.3. The pattern and primality

Let $`W\subset V_0`$ be the positive-clasp, zero-framing Whitehead pattern in an unknotted solid torus. Equivalently, take the standard Whitehead link $`W\cup A`$, with $`A`$ the unknotted axis and $`V_0=S^3\setminus\mathrm{Int}N(A)`$. Each component of this link is an unknot, its linking number is zero, and the pattern is geometrically essential in $`V_0`$. These are properties of this specified diagram: after the axis is removed the Whitehead component is an unknot; in the longitudinal cover of $`V_0`$, consecutive closed lifts of $`W`$ have linking number $`\pm1`$. The latter calculation is [Lemma 4.1](whitehead-pair.md). It proves that $`W`$ is not in a ball in $`V_0`$, and that no meridian disc misses $`W`$.

Set $`X=V_0\setminus\mathrm{Int}N(W)`$. A sphere in $`X`$ bounds a ball in $`V_0`$; that ball cannot contain $`W`$, since the pattern is not in a ball. Thus $`X`$ is irreducible. Its outer torus $`T=\partial V_0`$ is incompressible by [Lemma 4.1](whitehead-pair.md). Its pair of pants $`P`$ is incompressible by [Lemma 4.2](whitehead-pair.md), hence is $`\pi_1`$-injective by Hatcher's Corollary 3.3, printed p.59. It is boundary-incompressible by Hatcher's Lemma 1.11: it is not an annulus.

Glue $`X`$ to $`M=E(K_0)`$ by the zero framing. The companion is nontrivial, so $`\partial M`$ is incompressible. Amalgamated-product normal form shows that $`T`$ is incompressible in $`E(K')=X\cup_T M`$. In particular $`K'`$ is nontrivial: its exterior contains the injected torus group $`\mathbb Z^2`$, whereas an unknot exterior has group $`\mathbb Z`$.

**Lemma 7.2.** The knot $`K'`$ is prime, even though its companion $`K_0`$ is composite.

**First proof (genus).** The preceding torus-group argument proves $`K'`$ nontrivial, so $`g(K')\ge1`$. The standard Whitehead surface, obtained by plumbing the zero-framed companion annulus with a clasp Hopf annulus, has genus one. Hence $`g(K')=1`$. By Schubert's genus-additivity theorem, a decomposition $`K'=L_1\#L_2`$ with both factors nontrivial would give

```math
1=g(K')=g(L_1)+g(L_2)\ge2,
```

a contradiction. Thus $`K'`$ is prime. $`\square`$

**Second proof (decomposing annulus, independent of genus additivity).** Suppose a decomposing sphere for $`K'`$ splits it into two nontrivial knots. Its part in $`E(K')`$ is a properly embedded, non-boundary-parallel annulus $`A_d`$ with two meridian boundary curves. The annulus is incompressible: its core represents a meridian, whose image under the linking homomorphism is $`1`$.

Make $`A_d`$ transverse to $`T`$ and minimize their intersection by isotopy. Inessential intersection circles are removable using incompressibility and irreducibility. Consequently every remaining circle is essential in both surfaces. If any remains, the annular portion between a boundary component of $`A_d`$ and the first intersection circle lies in $`X`$. It would identify, up to sign, a meridian $`\mu_W`$ of $`W`$ with a curve on the outer torus in $`H_1(X)`$.

But the Whitehead-link homology calculation is

```math
H_1(X)=\mathbb Z[\mu_W]\oplus\mathbb Z[\mu_A],\qquad [\mu_{V_0}]=0,\qquad [\lambda_{V_0}]=[\mu_A].
```

Here the first equality is the meridian basis for a two-component link exterior; the second follows from linking number zero, and the third is the exchange of meridian and longitude for the unknotted axis. Thus the image of $`H_1(T)`$ is $`\mathbb Z[\mu_A]`$ and cannot contain $`\pm[\mu_W]`$. This excludes the annular portion. Therefore $`A_d`$ is entirely in $`X`$.

Now fill the outer boundary as for the unknotted companion. This restores $`E(W)`$, a solid torus because $`W`$ is an unknot in $`S^3`$. The annulus $`A_d`$ remains incompressible in that solid torus: its core is the meridian of $`W`$, hence a generator of $`\pi_1(E(W))`$. Hatcher's Lemmas 1.10 and 1.11, printed pp.19–20, imply it is boundary-parallel there. Its boundary slope is longitudinal for this solid torus, so **both** sides of $`A_d`$ are annulus products. To see the last point, one side is the parallelism $`A_d\times I`$; the other is a solid torus whose two boundary annuli also have primitive longitudinal cores, hence is $`S^1`$ times a rectangle with those annuli as opposite sides.

The solid torus $`N(A)`$ that was filled in is connected and disjoint from $`A_d`$, so lies entirely on one side of it. The product on the other side misses $`N(A)`$ and is contained in $`X`$. It makes $`A_d`$ boundary-parallel in $`X`$, and therefore in $`E(K')`$, contradicting the decomposing annulus. There is no nontrivial connected-sum decomposition. $`\square`$

## 7.4. Incompressibility and genus of the doubled surfaces

**Lemma 7.3.** If $`F`$ is an incompressible Seifert surface in $`M`$ of positive genus, then $`D(F)`$ is an incompressible, boundary-incompressible Seifert surface for $`K'`$, of genus $`2g(F)`$.

**Proof.**

The seams of $`D(F)`$ are two essential circles, separating its companion-side copies of $`F`$ from its pattern-side pair of pants. Assume $`g(F)\ge1`$ and $`F`$ incompressible. By Hatcher's Corollary 3.3, printed p.59, its inclusion is $`\pi_1`$-injective. All vertex groups in this three-piece surface decomposition are noncyclic free groups. A boundary word of a positive-genus, one-boundary orientable surface is not a proper power: in the standard cyclically reduced word $`\prod_{i=1}^g[a_i,b_i]`$, every signed generator occurs exactly once. A cyclically reduced proper power would repeat those occurrences. Boundary words of $`P`$ are also not proper powers, and its distinct boundary components represent nonconjugate cyclic subgroups.

Write

```math
\Gamma=\pi_1(E(K'))=G_M*_{C_T}G_X,\qquad C_T=\pi_1(T)\cong\mathbb Z^2.
```

Let $`\mathcal T_\Gamma`$ be its Bass–Serre tree. The surface decomposition of $`D(F)`$ gives its own graph of groups, with underlying graph a path of length two, vertex groups $`\pi_1(F_+),\pi_1(P),\pi_1(F_-)`$ and cyclic seam edge groups. Its tree maps equivariantly into $`\mathcal T_\Gamma`$.

This map is locally injective. At a companion vertex, two incident edges could have the same image only if an element of $`\pi_1(F)`$ outside the seam subgroup lay in $`C_T`$. Such an element would commute with the non-power boundary word, because $`C_T`$ is abelian. In a free group its centralizer is exactly the cyclic group generated by that word. Since $`F`$ is $`\pi_1`$-injective, this is a contradiction.

At a pattern vertex the same argument applies to two edges from the same boundary component of $`P`$. If edges from its two different outer boundaries had the same image, their cyclic stabilizers would lie in the same conjugate of $`C_T`$, and hence commute. The injection of $`\pi_1(P)`$ would then imply that conjugates of its two different boundary words commute in its free group. Their maximal cyclic subgroups would coincide, forcing the two boundary subgroups to be conjugate in $`\pi_1(P)`$. They are not: their generators have different abelianizations in $`H_1(P)`$. This too is impossible.

A locally injective map of trees is injective: an identification of two vertices would turn the unique joining path into a reduced nonempty closed path in a tree. The vertex-group injections together with this tree injection show that the homomorphism $`\pi_1(D(F))\to\Gamma`$ is injective. Indeed any kernel element fixes the image tree, hence the surface tree, and belongs to a vertex stabilizer on which the homomorphism is injective. This proves incompressibility of $`D(F)`$. It also proves the precise subgroup/tree identification used below.

Orient the copies of $`F`$ oppositely and match the induced seam orientations of $`P`$. The result is connected and orientable and has a single knot longitude boundary. Euler characteristic gives

```math
\chi(D(F))=-1+2(1-2g(F))=1-4g(F),\qquad g(D(F))=2g(F).
```

Since $`E(K')`$ is irreducible and its boundary is a torus, Lemma 1.11 of Hatcher also gives boundary-incompressibility of $`D(F)`$, which is not an annulus. Thus the displayed surfaces have the full vertex qualifications, without a minimum-genus assertion about them. $`\square`$

## 7.5. Disjointness

**Lemma 7.4.** If $`F,G`$ are disjoint Seifert surfaces in $`M`$, their doubled surfaces can be formed disjointly in $`E(K')`$.

**Proof.** Take disjoint small regular neighbourhoods of $`F`$ and $`G`$. Their traces on $`T`$ are disjoint annular neighbourhoods $`A_F,A_G`$ of their boundary longitudes. The two companion sheets for each double are the two sides of the corresponding regular neighbourhood.

Start with a pattern pair of pants $`P_F`$ whose two outer boundaries are $`\partial A_F`$. In the unsmoothed Whitehead surface $`P_F\cup A_F`$, the annulus $`A_F`$ lies on the same normal side of $`P_F`$ at its two ends; this is the oriented-plumbing fact proved in [Lemma 4.3](whitehead-pair.md). Push a parallel copy $`P_G`$ to the other side. Its two outer boundaries initially lie just outside $`A_F`$, in the connected complementary annulus $`T\setminus\mathrm{Int}A_F`$.

Within that annulus move this pair of boundary circles to $`\partial A_G`$, maintaining their order. The motion stays in a compact subannulus away from its ends. Extend it through a sufficiently thin boundary collar in $`X`$ disjoint from $`P_F`$. This gives $`P_G`$ disjoint from $`P_F`$ with precisely the required outer boundaries. Its one inner boundary is a distinct parallel knot longitude. The opposite orientations of the two outer boundaries permit attachment to the two opposite copies of $`G`$; interchange their labels if necessary. Rounding the four seams preserves disjointness, since the pieces and their collars were disjoint. $`\square`$

Apply this once to $`(V,U_0)`$. Extend $`\Psi`$ to $`E(K')`$ by the identity on $`X`$; its support lies strictly inside $`M`$, near $`T_B`$, and it fixes the chosen $`D(V)`$, all pattern pieces and seam collars. Consequently

```math
\Psi^n(D(U_0))=D(U_n)
```

is disjoint from the same fixed representative $`D(V)`$ for every $`n`$.

## 7.6. Recovering companion isotopy from the doubled surface

This argument extracts companion isotopy from the satellite surface group. It does not transport Banks's complementary-region list through the outer Whitehead pattern, which can join boundary-facing regions.

**Lemma 7.5.** Let $`M=E(L_1\#L_2)`$ with nontrivial factors. Let $`F,G\subset M`$ be connected, orientable, incompressible Seifert surfaces of the same positive genus. If the doubles $`D(F)`$ and $`D(G)`$ in a Whitehead satellite are ambient isotopic, then $`F`$ and $`G`$ are ambient isotopic in $`M`$, with boundary allowed to move.

**Proof.** First arrange their boundaries as the same parametrized preferred longitude by collar isotopies. Let $`L_F,L_G`$ be the images of $`\pi_1(D(F)),\pi_1(D(G))`$ in $`\Gamma=G_M*_{C_T}G_X`$. The tree embeddings of §7.4 identify the surface Bass–Serre trees with invariant subtrees of the ambient tree $`\mathcal T_\Gamma`$. Each is the unique minimal invariant subtree for its subgroup. Here both seam edge groups are proper subgroups of their endpoint noncyclic free vertex groups; hence the surface graph of groups is reduced, and its tree action is minimal. Equivalently, alternating elements outside a seam group have axes through its edge; translates of those axes cover both edge orbits.

An ambient isotopy induces the identity outer automorphism of $`\Gamma`$, so $`L_F`$ and $`L_G`$ are conjugate. Conjugation carries their unique minimal subtrees to one another. Their companion-type vertices have exactly two vertex orbits, with stabilizers the two copies of $`\pi_1(F)`$, respectively the two copies of $`\pi_1(G)`$. Thus it carries a companion vertex stabilizer onto a companion vertex stabilizer, not merely into one. At each such vertex there is a single orbit of incident seam edges.

Choose the source companion vertex and an incident seam edge as $`v_M=G_M`$ and $`e=C_T`$ in the ambient tree. After adjusting the conjugating element within $`L_G`$, its target companion vertex is one of two representatives. The first representative and its seam edge are $`v_M,e`$; the second are $`dv_M,de`$, where $`d`$ is the fixed path through $`P`$ between the two seams. In the second case, left multiplication by $`d^{-1}`$ identifies both with $`v_M,e`$ and identifies the second parallel copy of $`G`$ with the original one. This is an explicit group identification, not an assertion that an ambient isotopy preserves the companion torus.

The target companion vertex stabilizer has a single orbit of incident surface-tree seam edges. Adjust within that stabilizer to align the chosen edge as well as the vertex. The resulting conjugating element $`a`$ satisfies

```math
a\,\pi_1(F)\,a^{-1}=\pi_1(G),\qquad av_M=v_M,\qquad ae=e.
```

The edge equality, rather than just equality of its cyclic surface stabilizer, now gives directly

```math
a\in\mathrm{Stab}_{\Gamma}(e)=C_T=\langle\mu,\lambda\rangle.
```

The torus group is abelian, so $`a\lambda a^{-1}=\lambda`$, with the oriented preferred longitude preserved. No longitude-normalizer calculation or JSJ uniqueness assertion is needed.

Consequently the induced isomorphism $`\alpha`$ of the two free surface groups preserves their boundary word. The one-puncture Dehn–Nielsen–Baer theorem of Farb–Margalit, Theorem 8.8, printed p.234, realizes its outer class by a homeomorphism $`f:F\to G`$ preserving the boundary orientation. Truncate a small neighbourhood of the puncture end and adjust $`f`$ in the resulting boundary collar to agree with the boundary parametrization. Its based isomorphism and $`\alpha`$ differ by an inner conjugation $`c`$. Since both fix the boundary word $`w`$, $`c`$ centralizes $`w`$, hence is a power of $`w`$ in the free group. A boundary Dehn twist induces that inner conjugation and corrects it. Thus $`f`$ can realize the based isomorphism as well as the boundary marking.

The two maps $`i_F:F\to M`$ and $`i_G\circ f:F\to M`$ are properly homotopic. To include the boundary condition, realize the conjugating element $`a=\mu^r\lambda^s`$ (or its inverse, according to the based-map convention) as the trace of a boundary basepoint under a loop of translations of $`T`$. Extend those translations to a collar of $`T`$ in $`M`$. At the last time the boundary translation is the identity, since its displacement is an integral meridian-longitude vector. This is an ambient isotopy with moving boundary. After it, the two maps agree on their boundary parametrizations and induce the same based map on $`\pi_1`$.

The knot exterior is a $`K(\pi,1)`$ by Hatcher's Corollary 3.9, printed p.63. More explicitly, use a cell structure on $`F`$ consisting of its boundary circle, $`2g`$ based handle edges and one two-cell. Equality of the based maps on $`\pi_1`$ supplies homotopies on the handle edges while the boundary stays fixed; $`\pi_2(M)=0`$ extends these across the two-cell times $`I`$. This is a homotopy relative to the boundary. Choose a collar-straightened homotopy near that boundary and push every remaining interior point away from $`\partial M`$ along a collar; it is then a proper homotopy, with the same embedded endpoints.

Finally the surfaces are two-sided, incompressible and boundary-incompressible; boundary-incompressibility follows from Hatcher's Lemma 1.11 since they have positive genus. The companion exterior is compact, orientable, irreducible and boundary-irreducible. Waldhausen's homotopy-to-isotopy theorem, in the stated form, therefore makes them ambient isotopic. Boundary motion is permitted throughout the question. This proves the lemma. $`\square`$

Applying Lemma 7.5 to $`F=U_n,G=U_m`$ gives

```math
D(U_n)\simeq D(U_m)\quad\Longrightarrow\quad U_n\simeq U_m.
```

The latter is excluded for $`n\ne m`$ by [Lemma 5.1](obstruction.md), with $`F=Q`$, whose product-region proof survives the original connected sum. Therefore the satellite neighbours are pairwise nonisotopic.

## 7.7. Checklist and proof of the theorem

All target properties have the following proofs:

| Property | Argument |
|---|---|
| Specified knot | $`K'=W_0^+(B\#W_0^+(3_1))`$, with $`B`$ fixed by Banks Figure 1 |
| Primality | Lemma 7.2: genus one and Schubert additivity; a second proof excludes a decomposing annulus |
| Vertex qualifications | Lemma 7.3: orientability, connectedness, one preferred longitude, and $`\pi_1`$ injection |
| Fixed centre disjoint from every neighbour | Lemma 7.4 and the extension of $`\Psi`$ fixing $`D(V)`$ |
| Pairwise nonisotopy | Lemma 7.5 and Lemma 5.1 of [obstruction.md](obstruction.md) |
| Strict genus decrease | $`g(D(V))=6`$, $`g(D(U_n))=4`$ |

**Proof of Theorem 7.1.** Lemma 7.2 proves primality. Lemma 7.3 proves that $`D(V)`$ and every $`D(U_n)`$ define vertices of $`IS(K')`$, with genera $`6`$ and $`4`$. Lemma 7.4 gives disjoint representatives, with the centre fixed for every $`n`$. Lemma 7.5 and the companion nonisotopy prove that the $`u'_n`$ are pairwise distinct. They differ from $`v'`$ by genus, so are adjacent vertices. Thus the descending link of $`v'`$ contains infinitely many vertices of genus four. Since $`4<6`$, their complexities are smaller for any secondary area coordinate. This proves (F) fails for the specified prime satellite knot. $`\square`$

Neither the new neighbours nor the centre is asserted to be minimum genus. In particular Banks Theorem 1.8 is not being applied to these higher-genus surfaces. No mathematical property in the checklist is left as a conjecture. The bibliographic and verification limits for the declared standard external theorems remain exactly those in §7.2; no novelty or publication claim is made.
