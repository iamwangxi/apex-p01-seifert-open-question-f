# 1. The question and its meaning

[Overview](../README.md) · [Next: atoroidal exteriors](atoroidal.md) · [Sources](../sources/bibliography.md)

Condition (F) fails for knots in general. The composite counterexample has a genus-three vertex with infinitely many genus-two neighbours. A prime Whitehead satellite also fails (F): it has a genus-six vertex with infinitely many distinct genus-four neighbours; see [Theorem 7.1](prime.md). Atoroidal knot exteriors, by contrast, have only finitely many vertices at each genus bound.

## Target and conventions

The target [S] is Apex Intelligence, *Contractibility of the complex of incompressible Seifert surfaces: the knot case of Kakimizu's problem*, official competition edition, dated 11 September 2026, 48 printed pages. The PDF SHA-256 is:

`34f17d7d99780d3fd3626d9e5d7b35d6aa76661c404f191b6df341b300c0c06f`.

Let $`E(K)`$ be the compact exterior of an oriented knot $`K\subset S^3`$. A Seifert surface is a compact, connected, orientable, neatly embedded surface with one boundary component, a preferred longitude. Incompressibility means that there is no compression disc. By the Loop Theorem, an incompressible two-sided surface is also $`\pi_1`$-injective; see [H], Corollary 3.3, printed p.59. The disc case has trivial fundamental group.

A vertex of $`IS(K)`$ is an ambient isotopy class of such an incompressible surface. An ambient isotopy preserves $`\partial E(K)`$ setwise; boundary longitudes may move. Distinct vertices are adjacent exactly when they have disjoint representatives, including their boundary curves. These are [S], §4.1 and Definition 4.1, p.8. The same spanning-surface conventions appear in [K], Introduction, p.225. Boundary-incompressibility of a one-longitude incompressible Seifert surface is automatic; [S], Lemma 4.2, pp.8–9.

## Condition (F)

The competition paper uses the lexicographic complexity

```math
c(v)=(g(v),A(v)),
```

where $`A(v)`$ is its relative least-area invariant; [S], Definition 4.7, pp.10–11. For a vertex $`v`$, write $`N(v)`$ for its set of neighbours and

```math
L_c(v)=\{u\in N(v):c(u)\lt c(v)\}.
```

Condition (F) says that $`L_c(v)`$ is finite for every vertex. Remark 1.1, p.2, states that under (F), Theorem B reduces to the cited Morse lemma [S, reference 21, Lemma 2.3], together with the paper's heredity lemma. The closing paragraph of the Introduction, also p.2, leaves (F) as its one open question and identifies the equivalent question about infinitely many neighbours of strictly smaller genus.

To see the equivalence, separate the descending neighbours as

```math
L_c(v)=L_g(v)\cup L_A(v),
```

where

```math
L_g(v)=\{u\in N(v):g(u)\lt g(v)\},
```

and

```math
L_A(v)=\{u\in N(v):g(u)=g(v),\ A(u)\lt A(v)\}.
```

Lemma 4.8(i), p.11, says that for every fixed genus $`h`$ and every $`a>0`$, the entire set of vertices satisfying $`g(u)=h`$ and $`A(u)\le a`$ is finite. In particular $`L_A(v)`$ is finite. Thus, using that stated lemma, (F) is equivalent to finiteness of $`L_g(v)`$ for every $`v`$.

Both counterexamples are independent of Lemma 4.8(i): the inequalities $`2<3`$ and $`4<6`$ make the respective neighbours descending for any area values. The positive result is also independent of that lemma, since it proves the stronger assertion that all vertices of bounded genus form a finite set. None of these proofs requires the target's area-attainment, compactness, or exchange arguments.

## Subsequent author version

The author version [S2], arXiv:2609.09224v2, dated 12 September 2026, is by G. Pan, C. You, J. Zhou and Y. Chen and is titled *Exchange complexes and contractibility of the complex of incompressible Seifert surfaces*. It still asks this question in §1.5, p.5, and Remark 7.13, p.62. The latter explains that its same-genus part is finite by that version's Lemma 4.2(i), and that its countable Morse formulation does not require (F).

All target citations in the proof refer to the competition edition [S] unless [S2] is explicitly named. The source labels [B], [W], [K] and [H], with checked editions and printed page numbers, are specified in the [bibliography](../sources/bibliography.md).
