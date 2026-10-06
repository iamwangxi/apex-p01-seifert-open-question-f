# Bibliography and checked source editions

[Overview](../README.md) · [Question](../proof/question.md) · [Scope](../proof/scope.md)

The proof uses the editions below. All pinpoint citations are printed page numbers in the specified edition; preprint pages are not journal pages. Source statements and the figures needed for the construction were checked in the copies identified below, with the stated limits. Public acquisition or bibliographic routes are given here. No third-party full text or PDF is redistributed.

## [S] — Target competition paper

**Apex Intelligence.** *Contractibility of the complex of incompressible Seifert surfaces: the knot case of Kakimizu's problem*. Official competition edition, dated 11 September 2026, 48 printed pages.

Acquisition: the publicly released official competition PDF, `seifert-surfaces.pdf`. The precise edition is identified by PDF SHA-256:

`34f17d7d99780d3fd3626d9e5d7b35d6aa76661c404f191b6df341b300c0c06f`.

Checked and used:

- Remark 1.1 and the final paragraph of the Introduction, p.2: definition of (F), its Morse comparison, and the remaining open question.
- §4.1 and Definition 4.1, p.8: connected orientable surfaces, preferred longitude, ambient isotopies preserving the boundary setwise, and adjacency by disjoint representatives.
- Lemma 4.2 and its proof, pp.8–9: automatic boundary-incompressibility for one-longitude incompressible Seifert surfaces; the unknot discussion immediately following it, p.9.
- Definition 4.7, pp.10–11: lexicographic complexity $c=(g,A)$.
- Lemma 4.8(i), p.11: the stated finite same-genus, bounded-area set. Its analytic proof is not certified by this package and is not needed for any main theorem here.

## [S2] — Subsequent author edition

**Guancheng Pan, Chengsong You, Junwei Zhou and Yongchao Chen.** *Exchange complexes and contractibility of the complex of incompressible Seifert surfaces*. [arXiv:2609.09224v2](https://arxiv.org/abs/2609.09224v2), dated 12 September 2026.

Acquisition: the author preprint PDF from the version-specific arXiv record. PDF SHA-256:

`f3e9b5f1364886c3d88081c5082caffdd4fce5cd7ec8c529ab96fbeeb8becf64`.

Checked: §1.5, p.5, and Remark 7.13, p.62, continue to ask whether smaller-genus neighbours can be infinite. Remark 7.13 also states that the version's countable Morse comparison does not require (F). Its cited same-genus finiteness lemma is **Lemma 4.2(i)**, not competition Lemma 4.8(i). No certification of the other arguments in this later edition is asserted.

## [W] — Wilson's finite normal decomposition

**Robin T. Wilson.** *Knots with infinitely many incompressible Seifert surfaces*. **Checked edition:** [arXiv:math/0604001v2](https://arxiv.org/abs/math/0604001v2), dated 26 May 2006. Journal citation: *Journal of Knot Theory and Its Ramifications* **17** (2008), no.5, 537–551; the journal edition was not independently compared.

Acquisition: the version-specific arXiv preprint. PDF SHA-256:

`2cbcc594e6ac90bb05ad3030467cbfe46d9e7656b68a4fea31e8b407eac46e79`.

Checked and used in [Theorem 2.1](../proof/atoroidal.md):

- Main Theorem (Theorem 1), pp.1–2: nontrivial knot; finite incompressible Seifert bases and closed incompressible non-boundary-parallel summands; one base plus nonnegative integer coefficients represents every incompressible Seifert surface up to isotopy.
- §2, Definition 6, pp.3–4: Wilson's incompressibility convention excludes a sphere bounding a ball.
- §2, pp.4–5: normal-coordinate uniqueness and compatible normal Haken sums.
- §2, p.6: coordinate addition, Euler-characteristic additivity, and fundamental solutions.
- §4, proof of Main Theorem, pp.13–14, especially p.14: selection of the closed fundamental summands and removal of boundary-parallel tori.

The closed fundamental summands are connected by their coordinate indecomposability. Banks's qualification concerning the orientability of the bases is recorded below; the bounded-genus count uses fixed base Euler characteristics, not the bases' orientability or genus. Wilson's decomposition is an external theorem, not independently reproved here.

## [B] — Banks's explicit twist family and product-region criterion

**Jessica E. Banks.** *On links with locally infinite Kakimizu complexes*. **Checked edition:** [arXiv:1010.3831v2](https://arxiv.org/abs/1010.3831v2), dated 12 April 2011. The later journal edition was not independently compared.

Acquisition: the version-specific arXiv preprint. PDF SHA-256:

`3968d732d8e5ffa6ab9abfc2c48eecf0de863aae4c51689fa707d2b3ee59a00d`.

The specified preprint was read in full; the construction and critical figures were checked. Pinpoints:

- Definition 2.1, pp.2–3: product region, permitted collapsed boundary fibres, and the requirement that remaining vertical boundary lie on the ambient boundary.
- Proposition 2.2, p.3: the intersecting-to-disjoint product-region criterion for incompressible, boundary-incompressible surfaces in a boundary-irreducible Haken manifold. No minimum-genus hypothesis occurs in this proposition.
- Theorem 2.3, pp.3–5, and Figures 1–4: the twisted Whitehead double $B=K_\alpha$, genus-one surfaces $R,R_n$, meridional torus twist, and pairwise nonisotopy.
- Figure 3, p.4, and Figure 4 with the complementary-region calculation, p.5: disconnected horizontal faces and the nonproduct companion-side sutured pieces. The winding 2 and 3 interpretation uses the two solid tori in the trefoil's $(2,3)$ annular decomposition; it is explained in the present proof, not quoted as a numerical statement from Banks's prose.
- Remark 2.4, p.5: second-hand context for Kakimizu's doubled-surface construction; not an independently checked 1991 result.
- Theorem 3.6 and discussion, p.6: Wilson's omission concerning orientability of base spanning surfaces; least-weight normalisation is also noted there.
- Theorem 1.8, stated p.2 and proved pp.7–8: classification for local infinitude of **minimum-genus** neighbours. Its proof uses minimum genus to infer $\chi(S'')\ge0$; that step is not extended to arbitrary smaller-genus neighbours here.

## [K] — Kakimizu's spanning-surface complex

**Osamu Kakimizu.** *Finding disjoint incompressible spanning surfaces for a link*. *Hiroshima Mathematical Journal* **22** (1992), no.2, 225–236. Public bibliographic and acquisition route: [DOI 10.32917/hmj/1206392900](https://doi.org/10.32917/hmj/1206392900).

Acquisition: the journal PDF. PDF SHA-256:

`eb195635ce7ddb1c74caccae36d4493e875773f29de0f013eb91f5471c10b36c`.

Checked: the Introduction, p.225, defines ambient equivalence and the spanning-surface complexes; §3, p.231, observes that $IS(L)$ need not be locally finite, citing a 1991 example. That observation alone does not specify strictly smaller-genus neighbours and is not itself a counterexample to (F). Also checked for Remark 2.4: Theorem B, p.226, Proposition 3.5, p.232, and the note on non-fibred two-bridge knots with unique incompressible spanning surfaces, p.231. Also checked: the connected-sum collar model, pp.231–232, and the homotopy/product argument invoking Hempel and Waldhausen, pp.235–236. The latter is an indirect application, not a verbatim source for the standard relative-boundary corollary stated in [prime.md](../proof/prime.md).

## [H] — Hatcher's three-manifold notes

**Allen Hatcher.** *Notes on Basic 3-Manifold Topology*. Cornell University, author's online notes. Public acquisition route: [author's PDF](https://pi.math.cornell.edu/~hatcher/3M/3Mfds.pdf).

Checked edition: the author's PDF as downloaded on 4 October 2026, identified by SHA-256:

`c8add1a8633f36cb50de313f8f340a3f2b63b5548077d6e30f9c51a073398ff6`.

Checked and used: Lemmas 1.10–1.11, printed pp.19–20, for essential surfaces in a solid torus and the boundary-incompressibility/boundary-parallel-annulus alternative; Corollary 3.3 and its Loop Theorem proof, printed pp.59–60, for the compression-disc/$\pi_1$-injectivity equivalence for two-sided surfaces. The corollary's statement is on p.59. Corollary 3.9, printed p.63, gives asphericity for compact connected orientable irreducible three-manifolds with infinite fundamental group, as used for the companion knot exterior in the relative-boundary homotopy argument. These are three-manifold notes, not Hatcher's *Algebraic Topology*.

## [FM] — The punctured Dehn–Nielsen–Baer theorem

**Benson Farb and Dan Margalit.** *A Primer on Mapping Class Groups*. Princeton Mathematical Series **49**, Princeton University Press, 2012. **Checked edition:** the published book PDF, ISBN 978-0-691-14794-9, identified by SHA-256:

`c1d20309290cdcb3f8c0d22edc511b3abe0b8e6bb648d72e316e02a57fed0d93`.

Public bibliographic and acquisition route: Princeton University Press's catalogue under that ISBN, or an authorized library copy. The checked PDF is not redistributed here.

Checked and used: §8.2.7, **Theorem 8.8, printed p.234**. For a hyperbolic punctured surface it identifies the extended mapping class group with the outer automorphisms preserving the puncture peripheral conjugacy classes. In the one-boundary application, truncate a small neighbourhood of the puncture end and adjust the realizing homeomorphism in the resulting boundary collar. The proof separately fixes the oriented boundary word and corrects the based isomorphism by a boundary Dehn twist.

## Indirectly cited originals: limits of inspection

**Makoto Sakuma.** *Minimal genus Seifert surfaces for special arborescent links*. *Osaka Journal of Mathematics* **31** (1994), no.4, 861–905, Proposition 4.8(2). Public acquisition route: the journal's institutional archive or an authorized library copy. The original proposition and its precise printed page were not independently checked. Banks's Proposition 2.2 supplies the complete statement used here; the article range is bibliographic, not a checked pinpoint.

**Osamu Kakimizu.** *Doubled knots with infinitely many incompressible spanning surfaces*. *Bulletin of the London Mathematical Society* **23** (1991), no.3, 300–302, [DOI 10.1112/blms/23.3.300](https://doi.org/10.1112/blms/23.3.300). The original is behind a paywall and was not inspected. It is mentioned only as the work referenced by Banks's Remark 2.4 and Kakimizu 1992, p.231. No companion conditions, genus claims, direction of adjacency, or nonisotopy proof are certified from this unavailable original.

**Friedhelm Waldhausen.** *On irreducible 3-manifolds which are sufficiently large*. *Annals of Mathematics*, second series, **87** (1968), no.1, 56–88. Public bibliographic/acquisition route: the journal archive or an authorized library copy. **Indirectly cited; original not independently inspected.** The precise standard homotopy-to-isotopy form used, with proper relative-boundary homotopy and two-sided incompressible, boundary-incompressible embedded surfaces, is stated in [prime.md, §7.2](../proof/prime.md). Kakimizu 1992, pp.235–236, cites related homotopy/product machinery, including Waldhausen's Lemma 5.3. This is not claimed to identify or verify the original number and wording of the corollary used here.

**Horst Schubert — standard genus-additivity theorem.** Seifert genus is additive under connected sum: $g(L_1\#L_2)=g(L_1)+g(L_2)$. Used as a standard external theorem in the first proof of Lemma 7.2. **Original not independently inspected; no original theorem number or page is asserted.** The second proof of Lemma 7.2 is independent of this theorem.
