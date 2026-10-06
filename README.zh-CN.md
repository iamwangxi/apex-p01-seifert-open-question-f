# Seifert 曲面论文开放问题 (F) 的回答

**一般纽结中的答案是否定的，素纽结中也不成立：** 明确的合成纽结上，亏格 3 顶点有无穷多个两两不同痕的亏格 2 邻居；其素 Whitehead 卫星纽结上，亏格 6 顶点有无穷多个两两不同痕的亏格 4 邻居。**结外部无本质环面时，答案是肯定的：** 每个亏格上界内只有有限个顶点，所以 (F) 成立。

[English overview](README.md) · [完整英文证明](proof/question.md) · [文献与版本](sources/bibliography.md)

## 目标与主要结果

本仓库回答 Apex Intelligence 的 *Contractibility of the complex of incompressible Seifert surfaces: the knot case of Kakimizu's problem* 中的问题。目标是 2026 年 9 月 11 日、48 页的比赛版；开放问题位于印刷 p.2 的 Remark 1.1 及引言末段。目标 PDF 的 SHA-256 为：

`34f17d7d99780d3fd3626d9e5d7b35d6aa76661c404f191b6df341b300c0c06f`。

作者 G. Pan、C. You、J. Zhou、Y. Chen 的后续版本 arXiv:2609.09224v2（2026 年 9 月 12 日）仍在 §1.5、p.5 和 Remark 7.13、p.62 列出此问题。比赛版与作者版本的编号和页码分别注明。

论文按字典序使用复杂度 $c=(g,A)$。(F) 要求每个顶点的下降链环有限。比赛版 Lemma 4.8(i)、p.11 已使同亏格、较小面积的部分有限，剩下的拓扑问题是：一个顶点是否可能有无穷多个亏格严格更小的邻居。

- **Theorem A′（证明中的 Theorem 2.1）：** 若 $E(K)$ 没有不可压、非边界平行环面，则每个亏格上界内只有有限个不可压 Seifert 曲面同痕类。因此 (F) 成立；(F) 失败必须有本质环面。
- **Theorem B′（证明中的 Theorem 6.1）：** 取 Banks 的 Figure 1 明确给出的 twisted Whitehead double 为 $B$，取右手三叶结的正 clasp、零 framing Whitehead 双纽结 $J=W_0^+(3_1)$。对 $K=B\#J$，顶点 $[R\mathbin{\natural}H]$ 的亏格为 3，且有无穷多个不同的亏格 2 邻居 $[R_n\mathbin{\natural}Q]$。
- **Theorem C′（证明中的 Theorem 7.1）：** 对素纽结 $K'=W_0^+(B\#W_0^+(3_1))$，顶点 $v'=[D(R\mathbin{\natural}H)]$ 的亏格为 6，有无穷多个两两不同痕的亏格 4 邻居 $u'_n=[D(R_n\mathbin{\natural}Q)]$。其中 $D(F)$ 把两份反向平行的 $F$ 接到标准 Whitehead 配对裤的两条外边界上。

正面证明从 Wilson 的有限正规分解计数。反面证明把 Banks 的环面扭转族与 $J$ 上不交的异亏格曲面对组合，并证明连通和后乘积区域障碍仍成立：第二因子的每个补区域只经一个矩形接入，每张曲面只沿一个区间接入，因而不能合并旧补区域或接通原来不同的水平面片。素纽结扩展通过曲面群的树在卫星群树中的嵌入追回伴随曲面同痕，并控制外围边界后调用 Waldhausen 定理。素性主证明使用亏格 1 与 Schubert 可加性，另保留独立的分解环带证明。

## 仓库导览

| 文件 | 内容 |
|---|---|
| [proof/question.md](proof/question.md) | 问题的准确含义、顶点约定及与 Lemma 4.8(i) 的关系 |
| [proof/atoroidal.md](proof/atoroidal.md) | Theorem 2.1、Corollaries 2.2–2.3、Remark 2.4（逆命题不成立）；Wilson 定理及基底可定向性说明 |
| [proof/connected-sum.md](proof/connected-sum.md) | Lemmas 3.1–3.2；连通和的不可压性、亏格与不交性 |
| [proof/whitehead-pair.md](proof/whitehead-pair.md) | Lemmas 4.1–4.3；明确的亏格 1、2 不交曲面对 |
| [proof/obstruction.md](proof/obstruction.md) | Lemma 5.1；连通和后的乘积区域障碍 |
| [proof/counterexample.md](proof/counterexample.md) | Theorem 6.1 与构造核对清单 |
| [proof/prime.md](proof/prime.md) | Theorem 7.1；素卫星反例、树嵌入、不交性与伴随同痕抽取 |
| [proof/scope.md](proof/scope.md) | Morse 比较、Banks 分类不能直接推广的原因、依赖及复核范围 |
| [sources/bibliography.md](sources/bibliography.md) | 实际核对版本、印刷页码及公开获取途径 |
| [LICENSE](LICENSE) | CC BY 4.0 许可说明 |
| [MANIFEST.sha256](MANIFEST.sha256) | 除清单自身外全部仓库文件的 SHA-256 |

## 范围与复核

三项结论均为纯拓扑结果，不改变、也不依赖目标论文的面积和交换分析。在 Theorem B′、C′ 的纽结上，比赛版 Remark 1.1 记录的化简不可用，所以论文沿良序展开、不假设 (F) 的一般论证在这种一般性下确有必要。这并不指定唯一的证法：作者后续版本的可数 Morse 表述（v2 Corollary 7.12 与 Remark 7.13，p.62）同样不需要 (F)。这里解决的是有限性问题本身。

本仓库已给出合成反例与素反例；素反例仍是卫星纽结，外部有本质伴随环面，与 Corollary 2.2 一致。无本质环面是 (F) 成立的充分条件，但不是必要条件：Kakimizu 的一类合成纽结有本质环面，其 $IS(K)$ 却是一条直线，(F) 成立（Remark 2.4）。完整分类尚未给出。正面结果是 Wilson 已有定理的推论。没有完成穷尽的新颖性检索；在已核对的材料中，未见对此准确问题的回答。不声称各个构造材料都是新发现。

另一场 GPT-6.1 Sol 会话在全新上下文中对基础数学论证做了对抗复核，报告致命问题 0 项、需数学修补的问题 0 项。本稿已落实其三条表述澄清，并采用 Hatcher Lemma 1.11 简化边界不可压论证。素纽结扩展另经一次全新上下文对抗复核，致命问题 0 项、需数学修补的问题 0 项，并采用其两项证明简化和穿孔端表述澄清。证明明确使用外部定理；这不是形式化验证或人类专家认证。来源版本与未核原文的边界见文献表。

## AI 声明

GPT-6.1 Sol, in OpenAI Codex under human direction, developed the proof and drafted this text; a separate GPT-6.1 Sol session in a fresh context performed an adversarial review. Claude planned the work, checked key steps against the sources, and reviewed and edited the final text. No human expert has certified the work.

## 许可

本仓库原创散文、内容选择和编排在适用权利存在的范围内，采用 [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) 许可。引用时署名 `apex-p01-seifert-open-question-f` contributors，保留许可说明并注明修改。外部文献仍适用其自身的权利条款；仓库不附第三方全文或 PDF。详见 [LICENSE](LICENSE)。
