# 8. Scope, significance, and source limits

[Previous: the prime counterexample](prime.md) · [Overview](../README.md) · [Sources](../sources/bibliography.md)

The results answer the competition paper's stated open question negatively for knots in general and even for prime knots, and positively for all knots with atoroidal exteriors. Theorem 2.1 also proves the stronger bounded-genus finiteness statement. By Corollary 2.2, failure of (F) requires an incompressible, non-boundary-parallel torus in the exterior.

## The Morse comparison

Competition Remark 1.1, p.2, identifies a reduction of its combinatorial Theorem B to the cited Morse lemma under (F). Theorem 6.1 shows that this finite-descending-link reduction is unavailable for the specified knot and complexity. The general proof strategy must therefore accommodate infinite descending links, as the competition edition's transfinite induction along the well-order does.

This establishes a need for that additional generality in the competition argument. It does not single out one proof: the later author version, [S2], Corollary 7.12 and Remark 7.13, p.62, gives a countable Morse formulation that also applies without (F). The question that [S2] still lists as open is the finiteness assertion itself, which is what this package settles.

## Why Banks's Theorem 1.8 cannot simply be reused

Banks's Theorem 1.8 concerns local infinitude in the complex of **minimum-genus** Seifert surfaces. In its proof, [B], pp.7–8, surgery across a torus produces a new Seifert surface $`R''`$ and a closed surface $`S''`$. Minimum genus gives the Euler-characteristic comparison that implies

```math
\chi(S'')\ge0.
```

The relevant companion-side pieces must then be annuli. This is what leads to Banks's restriction to a torus-knot, cable-knot, or connected-sum companion with winding number zero.

A neighbour of a higher-genus vertex, even if its genus is strictly smaller, need not have minimum genus among all Seifert surfaces. Its being smaller than that fixed vertex provides no substitute for the comparison with $`R''`$. The companion restriction therefore does not follow for arbitrary descending neighbours, and is not claimed here.

Wilson's global normal decomposition supplies only the necessary existence of an essential torus. It does not, by this argument alone, give a zero winding number, a torus disjoint from the fixed vertex, or a classification of companions.

## Dependence and limitations

All three main results are topological. They neither modify nor depend on the target's area-attainment, compactness, least-area exchange, or boundary-regularity proofs. Using Lemma 4.8(i) to explain the target's formulation is distinct from using it to prove any main result: none of the proofs does so.

The finiteness theorem is a direct consequence of Wilson's finite normal decomposition. That decomposition is invoked as an external theorem. Banks's explicit twist family and the product-region criterion are also external inputs; the unequal-genus pair, connected-sum incompressibility, and obstruction transport are proved in this package. Banks's original family alone has genus-one neighbours of a genus-one vertex and does not refute (F).

Theorem 7.1 gives a prime counterexample in addition to the composite knot of Theorem 6.1. It is still a satellite knot: the Whitehead companion torus is essential, consistently with Corollary 2.2. Remark 2.4 shows that an essential torus alone does not force failure: Kakimizu's composite knots with a line-shaped $`IS(K)`$ satisfy (F). A complete classification of knots satisfying (F) has not been carried out.

The checked editions are Banks's arXiv v2 and Wilson's arXiv v2, not independently compared journal editions. Sakuma's original Proposition 4.8(2) is used through Banks's complete quotation. Kakimizu 1992, p.231, cites Kakimizu's 1991 note on doubled knots for the fact that $`IS(L)`$ need not be locally finite, and Banks's Remark 2.4, p.5, describes its construction. Neither description presents a vertex with infinitely many neighbours of smaller genus. The 1991 note itself was not accessible to us, and nothing in the argument depends on it.

For the prime extension, Farb–Margalit's punctured Dehn–Nielsen–Baer theorem and Hatcher's asphericity corollary were checked in the specified editions. Schubert's genus additivity and Waldhausen's relative-boundary homotopy-to-isotopy theorem are explicit standard external inputs whose originals were not independently inspected. The second primality proof avoids genus additivity. The tree and peripheral arguments verify the hypotheses of the stated Waldhausen form; Kakimizu's use of related machinery is not presented as a verbatim check of that form.

No exhaustive priority search has been performed. In the sources examined, and in a limited web search, we found no answer to this precise finite-descending-link question. This is a report of the inspected sources, not a claim that the construction, its ingredients, or the observation has no predecessor.

## Review status

A separate GPT-6.1 Sol session in a fresh context adversarially reviewed the underlying English mathematical argument and its sources. It reported that the two main conclusions hold, with **0 fatal issues and 0 issues requiring mathematical repair**. Three presentation clarifications were recommended and are incorporated here: explicitly citing the Loop Theorem; separating the parallel boundary longitude before summing; and taking Wilson's connected closed fundamental summands directly. Its suggested use of Hatcher's Lemma 1.11 is also incorporated.

The prime-knot proof received a further adversarial review in a fresh context, reporting **0 fatal issues and 0 issues requiring mathematical repair**. Its two confirmed simplifications are incorporated: genus one and genus additivity for primality, and simultaneous alignment of the ambient vertex and edge to obtain the peripheral conjugating element directly. Its puncture-end wording clarification is also adopted.

The reviews accept accurately stated external theorems with their hypotheses verified. They are not formal verifications of three-dimensional topology, expert certifications, validations of the target's analytic arguments, or priority determinations.
