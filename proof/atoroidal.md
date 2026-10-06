# 2. Positive result: atoroidal exteriors

[Previous: the question](question.md) · [Next: connected sums](connected-sum.md) · [Sources](../sources/bibliography.md)

**Theorem 2.1.** Suppose that $E(K)$ contains no incompressible, non-boundary-parallel torus. For every integer $h$, there are only finitely many vertices of $IS(K)$ of genus at most $h$. Consequently $IS(K)$ satisfies (F), for the complexity in [S], or indeed for any lexicographic complexity whose first coordinate is genus.

**Proof.** The unknot has just the meridian-disc vertex; [S], §4.1, p.9. Assume $K$ is nontrivial. Wilson's Main Theorem (Theorem 1), [W], pp.1–2, gives finite lists of incompressible Seifert base surfaces $S_i$ and closed incompressible surfaces $Q_j$, none of the latter boundary-parallel, such that every incompressible Seifert surface is isotopic to a Haken sum with one base and nonnegative integer closed-surface coefficients. In his fixed triangulation this is an admissible normal sum

$$
S_i+\sum_j a_j Q_j,\qquad a_j\in\mathbb Z_{\ge0}.
$$

Here “Haken sum” is the normal sum in a fixed triangulation. A normal coordinate vector specifies a surface up to normal isotopy; it is not an arbitrary choice of resolutions along intersections. See [W], §2, pp.4–5. Wilson removes boundary-parallel tori in the proof, p.14; retaining those zero-Euler-characteristic summands would invalidate the following count.

Take Wilson's closed incompressible, non-boundary-parallel fundamental summands, as selected in the proof of his Main Theorem, §4, p.14. Each is connected: if a closed fundamental normal surface were disconnected, its components would give nonzero closed solutions of the same modified normal equations whose sum is its coordinate vector, contradicting fundamentality. No splitting or extra claim about disconnected essential surfaces is needed. A closed surface embedded in $S^3$ is orientable. No sphere is an incompressible summand in the irreducible knot exterior, under Wilson's convention ([W], Definition 6, pp.3–4). By the hypothesis, no $Q_j$ is a torus. Therefore

$$
d_j=-\chi(Q_j)\ge2.
$$

Euler characteristic is additive under normal Haken sum, [W], p.6. If $g(S)\le h$, then

$$
1-2h\le\chi(S)=\chi(S_i)-\sum_j a_j d_j,
\qquad
\sum_j a_jd_j\le\chi(S_i)-1+2h.
$$

For a fixed $i$ put $b_i=\chi(S_i)-1+2h$. If $b_i\ge0$, every coefficient satisfies

$$
0\le a_j\le\left\lfloor b_i/d_j\right\rfloor.
$$

Thus the coefficient choices are finite. A negative right-hand side permits no representation; an empty list of $Q_j$ permits only the base. There are finitely many $i$ and finitely many permitted coefficient vectors. Each admissible vector determines at most one normal isotopy class of the sum. Hence there are finitely many ambient isotopy classes of the stated genus bound.

All descending neighbours of a vertex $v$ lie among the vertices of genus at most $g(v)$. The stronger finiteness just proved therefore proves (F) without using the area-finiteness lemma. $\square$

**Source caveat that does not affect this count.** Banks points out an orientability omission in Wilson's treatment of the base surfaces, [B], p.6. The proof above only needs a finite list of bases with fixed Euler characteristics. It does not need those bases themselves to be orientable, or to have their genera defined. The closed summands are orientable because they are embedded closed surfaces in $S^3$. Thus the counting argument survives the stated base-orientability issue. Wilson's finite normal decomposition is used as a published external theorem, not independently reproved here.

**Corollary 2.2.** If some vertex has infinitely many neighbours of strictly smaller genus, then $E(K)$ contains an incompressible, non-boundary-parallel torus.

**Proof.** The neighbours have a common genus bound, so apply Theorem 2.1 contrapositively. $\square$

**Corollary 2.3.** If $E(K)$ has no closed essential surface at all, then $IS(K)$ itself has finitely many vertices.

**Proof.** Wilson's closed-summand list is empty. $\square$

“No closed essential surface” means no closed incompressible non-boundary-parallel surface; a nontrivial knot exterior always has a boundary-parallel incompressible torus. The theorem applies in particular whenever the exterior is atoroidal. We do not infer Banks's more restrictive list of possible companions from this corollary: that list in [B], Theorem 1.8, concerns infinitely many *minimal-genus* neighbours.

**Remark 2.4 (atoroidality is not necessary).** The converse of Theorem 2.1 fails. Let $K=K_1\#K_2$, where each $K_i$ is non-fibred and has a unique incompressible Seifert surface; Kakimizu notes that there are many non-fibred two-bridge knots of this kind, [K], p.231. By [K], Theorem B, p.226, and Proposition 3.5, p.232, every incompressible Seifert surface of $K$ is equivalent to one of Eisner's minimum-genus surfaces $S^{(n)}$, $n\in\mathbb Z$, and $d([S^{(n)}],[S^{(k)}])=|n-k|$. Thus $IS(K)=MS(K)$ is a line: every vertex has exactly two neighbours, both of the same genus, and (F) holds. Yet the exterior of a composite knot contains an essential swallow-follow torus. An essential torus is therefore necessary for the failure of (F) but does not force it; Theorems 6.1 and 7.1 show that failure does occur.
