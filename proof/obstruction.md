# 5. Persistence of Banks's product-region obstruction

[Previous: the Whitehead pair](whitehead-pair.md) · [Next: the counterexample](counterexample.md) · [Sources](../sources/bibliography.md)

Let $`B`$ be the twisted Whitehead double $`K_\alpha`$ of the trefoil shown in [B], Figure 1, p.3. Let $`R`$, $`R_0`$, $`T_B`$ and $`\Psi`$ be Banks's genus-one surfaces, companion torus and meridional torus twist in Theorem 2.3, pp.3–5, Figures 1–4. Thus

```math
R_n=\Psi^n(R_0),\qquad g(R)=g(R_n)=1\quad(n\in\mathbb Z).
```

Banks proves that the $`R_n`$ are pairwise nonisotopic and that each can be made disjoint from $`R`$. Push $`R`$ into the pattern side, away from a sufficiently small twisting collar, so that $`\Psi(R)=R`$. Since $`\Psi`$ is supported near $`T_B`$, the entire family agrees near $`\partial E(B)`$. The Figure 1 knot fixes the first factor without imposing a separate numerical framing convention.

## The criterion being used

A product region between surfaces $`S,S'`$ is the embedded image of

```math
T^*=(T\times[0,1])/\mathord{\sim},
```

where $`T`$ is a compact surface and $`\sim`$ collapses $`x\times[0,1]`$ for each $`x`$ in a finite collection of arcs and circles $`\rho\subseteq\partial T`$. Its horizontal faces are precisely its intersections with $`S`$ and $`S'`$, and

```math
\partial T^*\setminus(T\times\{0,1\})\subseteq\partial M.
```

This is [B], Definition 2.1, pp.2–3. In particular, uncollapsed vertical boundary cannot be left in the interior of $`M`$.

Banks's Proposition 2.2, p.3, states: in a boundary-irreducible Haken manifold, two properly embedded incompressible, boundary-incompressible surfaces in general position that intersect but can be isotoped to be disjoint must bound a product region. This criterion has no minimum-genus hypothesis. Banks attributes it to Sakuma, Proposition 4.8(2); we use the complete statement as given by Banks and do not claim an independent check of Sakuma's original proof.

## Lemma 5.1

**Lemma 5.1.** For a fixed incompressible Seifert surface $`F`$ of a knot $`J`$, the surfaces $`R_n\mathbin{\natural}F`$ in $`E(B\#J)`$, with their joining band in the fixed knot-boundary collar, are pairwise nonisotopic.

**Proof.** Incompressibility follows from [Lemma 3.1](connected-sum.md). Extend $`\Psi`$ by the identity on the second summand. Applying $`\Psi^{-n}`$ reduces a comparison of indices $`n,m`$ to indices $`0,k`$, where $`k=m-n\ne0`$.

Take Banks's parallel copy $`R'_0`$ of $`R_0`$. In her description, p.4, the copy is disjoint in the interior and retains the same boundary. Before making the connected sum, move the boundary of $`R'_0`$ to a **distinct parallel preferred longitude** in a boundary collar disjoint from the twisting support. The two interiors remain disjoint outside the twisting collar. This is an allowed ambient isotopy because boundary curves may move. Take an adjacent disjoint parallel copy $`F'`$ of $`F`$ in the second summand and match the two joining arcs in boundary order. Compare the representatives

```math
S=R_0\mathbin{\natural}F,
\qquad
S'=\Psi^k(R'_0)\mathbin{\natural}F'.
```

They intersect transversely in the twisting collar and have distinct boundary longitudes. Opening the coincident boundary of Banks's model in this way opens its boundary corner into a strip with vertical boundary on the exterior boundary. It does not merge complementary components or connect distinct horizontal face pieces.

### The original obstructions

A horizontal face means the portion of one of the surfaces incident to the closure of a complementary component, with the surface cut along the intersection curves. Banks's Figure 4 and its accompanying text, p.5, exhaust the complementary component types. The types $`M_{0,a}`$, $`M_{0,b}`$, $`M_{1,b}`$ and $`M_T`$ have disconnected $`R_0`$-face. The trefoil-side pieces $`M_{1,a}`$ and $`M'_{1,a}`$ are the two nonproduct sutured pieces described using Figure 3, p.4. Their annular sutures wind respectively 2 and 3 times in solid tori. An annulus product has winding 1, so neither is an annulus product.

The text treats any nonzero twist, although Figure 4 illustrates $`k=2`$. Increasing $`|k|`$ repeats the collar types; reversing the sign reverses the collar picture. Neither operation removes the disconnected-face obstruction or changes the trefoil-side suture windings to 1.

### Why complementary components cannot merge

Choose the decomposing meridional annulus $`A`$ in the fixed knot-boundary collar, outside the twist support. It meets $`S`$ and $`S'`$ in two disjoint spanning arcs. Cutting along the arcs leaves two rectangles $`D_{\mathrm{in}}`$ and $`D_{\mathrm{out}}`$.

In the second summand, the complement of the adjacent parallel surfaces $`F,F'`$ has exactly two regions: the parallel region $`C_{\mathrm{in}}`$ between them and the connected outside region $`C_{\mathrm{out}}`$. The parallel region has interior $`F\times(0,1)`$. The outside region is connected because a connected Seifert surface with one longitude boundary is nonseparating; cutting the exterior along it leaves a connected manifold. One joining rectangle meets $`C_{\mathrm{in}}`$ and the other meets $`C_{\mathrm{out}}`$.

Each new region therefore attaches through just **one** rectangle to one old Banks region. The attachments have the form

```math
M_\alpha\cup_{D_{\mathrm{in}}}C_{\mathrm{in}},
\qquad
M_\beta\cup_{D_{\mathrm{out}}}C_{\mathrm{out}}.
```

No region in the added summand meets both rectangles and thereby joins two different old regions. If $`M_\alpha=M_\beta`$, the same old region receives two attachments; distinct old regions still do not merge. Both new regions meet a joining rectangle, so there is no additional complementary region entirely contained in the second summand.

### Why horizontal face pieces cannot connect

The joining interval lies outside all twist intersection curves, in one specified piece of $`R_0`$ cut along those curves. The connected surface $`F`$ attaches along that single interval. It enlarges that piece but cannot connect it to another old piece. The same argument applies to the $`S'`$-face using $`F'`$.

If both rectangles are incident to the same old region, their $`R_0`$ edges are the two sides of the same spanning arc in the same face piece. They are not intervals in two different face pieces. Thus even this case cannot turn a disconnected horizontal face into a connected one. The trefoil-side pieces receive no attachment: the joining annulus lies on the pattern-side knot boundary, away from $`T_B`$.

| Original region type | Obstruction | Effect of adjoining the second summand |
|---|---|---|
| $`M_{0,a},M_{0,b}`$ | Disconnected horizontal face | $`F`$ attaches along one interval to one face piece; other pieces remain separate |
| $`M_{1,b},M_T`$ | Disconnected horizontal face | Unchanged, away from the joining annulus |
| $`M_{1,a},M'_{1,a}`$ | Suture winding 2 or 3, whereas an annulus product has winding 1 | Unchanged in the companion exterior |

### Exhaustion and application of the criterion

These obstructions exclude all product regions, not just the entire manifold being a product. If a product region existed, restrict to a connected component of its base $`T`$. Its three-dimensional interior would be disjoint from $`S\cup S'`$. By Definition 2.1, it has no frontier in the interior of $`M\setminus(S\cup S')`$: its remaining boundary lies on $`\partial M`$, or is collapsed onto $`S\cap S'`$. Thus that interior is an entire complementary component. The horizontal face of a connected base has connected interior. The disconnected-face components cannot supply it, and the untouched sutured solid tori cannot supply an annulus product. An arbitrarily chosen small parallel patch inside a region would have unallowed vertical boundary in the manifold interior and is not a product region in this definition.

The exterior $`E(B\#J)`$ is irreducible and boundary-irreducible because $`B\#J`$ is nontrivial. The incompressible Seifert surfaces make it Haken. By Lemma 3.1, $`S,S'`$ are incompressible. They are boundary-incompressible by the one-longitude knot-surface argument [S], Lemma 4.2, pp.8–9. They are properly embedded, in general position, and intersect for $`k\ne0`$.

If $`S`$ and $`S'`$ were isotopic, $`S`$ could be isotoped to a disjoint parallel copy of $`S'`$, including at the boundary. Proposition 2.2 would then force a product region, which we have excluded. Hence they are not isotopic. Undoing $`\Psi^{-n}`$ proves pairwise nonisotopy for the full family. No general injectivity theorem for connected-sum surface classes has been assumed. $`\square`$
