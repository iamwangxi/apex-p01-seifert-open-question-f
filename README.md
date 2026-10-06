# The Seifert-surface paper's open question (F)

**The answer is negative for knots in general and even for prime knots:** a specified composite knot has a genus-three vertex with infinitely many distinct genus-two neighbours, and its prime Whitehead satellite has a genus-six vertex with infinitely many distinct genus-four neighbours. **For atoroidal knot exteriors the answer is positive:** there are only finitely many vertices at every genus bound, so (F) holds.

[中文说明](README.zh-CN.md) · [Full proof](proof/question.md) · [Bibliography](sources/bibliography.md)

## Target and main results

This package answers the open question in Remark 1.1 and the closing paragraph of the Introduction, printed p.2, of Apex Intelligence, *Contractibility of the complex of incompressible Seifert surfaces: the knot case of Kakimizu's problem*, official competition edition, dated 11 September 2026, 48 printed pages. Its PDF SHA-256 is:

`34f17d7d99780d3fd3626d9e5d7b35d6aa76661c404f191b6df341b300c0c06f`.

The later author version, arXiv:2609.09224v2 (12 September 2026), by G. Pan, C. You, J. Zhou and Y. Chen, still lists the question in §1.5, p.5, and Remark 7.13, p.62. Editions and checked source locations are distinguished in the bibliography.

For the target's lexicographic complexity $c=(g,A)$, (F) requires each descending link to be finite. Its Lemma 4.8(i), p.11, makes the same-genus, smaller-area part finite. The remaining question is whether a vertex can have infinitely many neighbours of strictly smaller genus.

- **Theorem A′ (Theorem 2.1 in the proof).** If $E(K)$ contains no incompressible, non-boundary-parallel torus, then for each integer $h$ only finitely many vertices of $IS(K)$ have genus at most $h$. Thus (F) holds. Failure of (F) requires an essential torus.
- **Theorem B′ (Theorem 6.1 in the proof).** Let $B$ be the twisted Whitehead double $K_\alpha$ of the trefoil in Banks's Figure 1, and let $J=W_0^+(3_1)$ be the positive, zero-framing Whitehead double of the right-handed trefoil. For $K=B\#J$, the vertex $[R\mathbin{\natural}H]$ has genus 3 and has infinitely many distinct genus-two neighbours $[R_n\mathbin{\natural}Q]$.
- **Theorem C′ (Theorem 7.1 in the proof).** For the prime knot $K'=W_0^+(B\#W_0^+(3_1))$, the vertex $v'=[D(R\mathbin{\natural}H)]$ has genus 6 and has infinitely many pairwise distinct genus-four neighbours $u'_n=[D(R_n\mathbin{\natural}Q)]$. Here $D(F)$ attaches two oppositely oriented parallel copies of $F$ to the two outer boundaries of the standard Whitehead pair of pants.

Wilson's finite normal decomposition supplies Theorem A′. Theorem B′ uses Banks's torus-twist family, an incompressible disjoint pair of genera 1 and 2 on $J$, and a proof that Banks's product-region obstruction survives the stated connected sum. The added summand cannot merge old complementary regions or connect their disconnected horizontal face pieces. Theorem C′ uses an embedded surface-group tree in the satellite-group tree to recover companion isotopy, with peripheral boundary control and Waldhausen's theorem. Primality follows from genus one and Schubert additivity; an independent decomposing-annulus proof is also given.

## Reading the proof

| File | Content |
|---|---|
| [proof/question.md](proof/question.md) | Exact question, surface conventions, and relation to Lemma 4.8(i) |
| [proof/atoroidal.md](proof/atoroidal.md) | Theorem 2.1, Corollaries 2.2–2.3, and Remark 2.4 (the converse fails); Wilson's theorem and the orientability caveat |
| [proof/connected-sum.md](proof/connected-sum.md) | Lemmas 3.1–3.2: incompressibility, genus, and disjointness |
| [proof/whitehead-pair.md](proof/whitehead-pair.md) | Lemmas 4.1–4.3: the explicit unequal-genus pair |
| [proof/obstruction.md](proof/obstruction.md) | Lemma 5.1: persistence of the product-region obstruction |
| [proof/counterexample.md](proof/counterexample.md) | Theorem 6.1 and construction checklist |
| [proof/prime.md](proof/prime.md) | Theorem 7.1: the prime satellite, tree embeddings, disjointness, and companion-isotopy extraction |
| [proof/scope.md](proof/scope.md) | Morse comparison, limits of Banks's classification, dependence, and review status |
| [sources/bibliography.md](sources/bibliography.md) | Exact editions, checked printed pages, and public acquisition routes |
| [LICENSE](LICENSE) | CC BY 4.0 license notice |
| [MANIFEST.sha256](MANIFEST.sha256) | SHA-256 of every other repository file |

## Scope and review

All three results are topological and neither modify nor depend on the target's area or exchange analysis. For the knots of Theorems B′ and C′ the reduction recorded in competition Remark 1.1 is unavailable, so the paper's general argument along the well-order, which does not assume (F), is needed in that generality. This does not single out one proof: the later author version's countable Morse formulation (v2, Corollary 7.12 and Remark 7.13, p.62) also works without (F). What is settled here is the finiteness question itself.

The package gives both a composite counterexample and a prime counterexample. The prime knot is still a satellite, with an essential companion torus, consistently with Corollary 2.2. Atoroidality is sufficient for (F) but not necessary: Kakimizu's composite knots whose $IS(K)$ is a line satisfy (F) despite an essential torus (Remark 2.4). A full classification is not treated. The positive result is a consequence of Wilson's existing theorem. No exhaustive novelty search has been performed; the sources examined contain no answer to this precise question. The package does not claim that its ingredients are new.

An independent GPT-6.1 Sol session adversarially reviewed the underlying mathematical argument in a fresh context, reporting 0 fatal issues and 0 issues requiring mathematical repair. Its three presentation clarifications and its suggested application of Hatcher's Lemma 1.11 are incorporated. The prime-knot extension received a further adversarial review in a fresh context, also reporting 0 fatal issues and 0 issues requiring mathematical repair. Its two proof simplifications and its puncture-end wording clarification are incorporated. This is a conventional proof using explicit external theorems, not a formal or human-expert certification. Source-version limits are recorded in the bibliography.

## AI disclosure

GPT-6.1 Sol, in OpenAI Codex under human direction, developed the proof and drafted this text; a separate GPT-6.1 Sol session in a fresh context performed an adversarial review. Claude planned the work, checked key steps against the sources, and reviewed and edited the final text. No human expert has certified the work.

## License

Original prose and the original selection and arrangement of this package are licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/), to the extent applicable rights exist. Attribute the material to the `apex-p01-seifert-open-question-f` contributors, retain the notice, and indicate changes. External publications retain their own terms; no third-party full text or PDF is bundled. See [LICENSE](LICENSE).
