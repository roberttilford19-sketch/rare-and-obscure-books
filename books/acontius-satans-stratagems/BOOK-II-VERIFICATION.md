# BOOK II — VERIFICATION

**Jacopo Acontius, *Satanae Stratagematum* (Basel, 1565) — Book II, fresh English translation from the page images of the 1631 Latin (IA b3033018x), per the frozen Stage 0 control sheet.**

Verification performed 2026-10-25 by the translating crew and the coordinator, against the page images. **Result, with its caveat in the same breath: Book II is complete and stands verified at every check the desk runs — every leaf of the true span present exactly once, every inter-page seam checked, a three-page word-by-word second pass clean on all three pages — but the book's true span is NOT the span the control sheet states: Book II ends at the head of printed p. 101, not at the foot of p. 104, and one of the three sampled leaves' machine counts (p. 99) does not reconcile and never will, because the OCR stream for that leaf is corrupted by show-through ghost text. Both facts are stated in full below; neither is hidden in a footnote.** The translation is a DRAFT under the Acontius rebuild's standing fences — no shelf or clone writes, no pushes, no uploads; Book III has not been started.

---

## 1. Leaf completeness — mechanically confirmed, on the corrected span

**The boundary discrepancy, stated plainly.** The control sheet and the Stage 0 scoping place Book II's end at the foot of printed p. 104. The page images say otherwise, and the images govern: printed p. 101 (leaf n128) opens with the completion of Book II's final sentence ("… cum satis multa dicta sint, de authoritate deinceps est dicendum."), and immediately below it stands the heading *SATANAE STRATAGEMATVM / LIBER TERTIVS* with Book III's opening text (drop-initial C, "CVM authoritatem qua erroribus …") — and p. 101's running head already reads TERTIVS, with signature G 3. Book II's true span is therefore: **from the Book II heading mid-p. 56** (below Book I's closing sentence "Sed iam ad reliqua pergamus.") **through p. 100, plus the ten-word completion at the head of p. 101.** The control sheet's boundary is wrong by three pages; the knock-on effect — Book III's span begins mid-p. 101, and both books' Stage 0 Latin denominators were aggregated over the wrong boundary — is recorded here for the Book III build to inherit. Stage 0's figure for Book II, 8,161 cleaned words, was aggregated over leaves running to n130 and so includes Book III leaves n129, n130, and the body of n128.

**Completeness on the true span.** The translation's structure was checked mechanically: **45 page sections, printed pp. 56–100, each exactly once** (pp. 56–68, 13 sections; 69–81, 13; 82–94, 13; 95–100, 6), plus the p. 101 completion carried inside p. 100's section by the project's carry convention (a sentence is rendered where it completes). Every leaf of the span is thereby accounted for: leaves n83–n127 by their page sections, leaf n128 by the completion carried in p. 100's section and by the exclusion record below. The boundary leaves were read directly by the coordinator: leaf n83 (Book II's heading and opening, beneath Book I's close), leaf n128 (the completion and Book III's heading), and leaf n130 (Book III text throughout, no Book II matter).

**Exclusions, named.** Nothing after the completion sentence on p. 101 is Book II, and none of it was translated into this book: the whole of Book III's opening on p. 101 and pp. 102–104 entire, including two Book III marginal notes on the excluded leaves (p. 102, on emissaries sent to learn what is done elsewhere; p. 104, on the godly man's duty toward others erring in religion), which the chunk log names so the Book III build inherits them. The first chunk of the build (pp. 56–68) was translated before the boundary was settled and its working notes conjectured a possible overlap with Book I on p. 56; the images settle it — Book I closes and Book II opens on the same page with no shared text, and no sentence is translated twice.

## 2. Word counts and the ratio — stated as description, on every defensible denominator

**English body: 11,912 words** (mechanically counted on the integrated translation body: front matter, headings, and marginal notes excluded).

**Latin denominators, all of them stated:**

| Denominator | Figure | Ratio (11,912 ÷ figure) |
|---|---|---|
| Stage 0's Book II figure (cleaned djvu, wrong span — includes Book III leaves) | 8,161 | **1.460** |
| That figure corrected at Stage 0's measured 95.4% djvu recovery | 8,554 | 1.393 |
| Boundary-corrected cleaned djvu (leaves n83–n127 = 7,642, plus the 10 hand-counted completion words on n128) | 7,652 | **1.557** |
| Boundary-corrected figure at the same 95.4% recovery | 8,021 | 1.485 |

Per-range cleaned Latin on the corrected span: pp. 56–68, 2,221; pp. 69–81, 2,184; pp. 82–94, 2,111; pp. 95–100, 1,126, plus the 10 completion words.

**The band, labelled as what it is.** The house working band for this rebuild (English/Latin ≈ 1.28–1.46) is a heuristic derived from a single benchmark — the 1648 English against its Latin — not a standard, and these ratios are description, not verdict. On every denominator above, Book II's ratio sits at or above the band's top edge, in the same posture as Book I (1.446–1.517 across its denominators). One further caution belongs on the record, arising from §4: the three-page sample's djvu counts, pooled, run 7.4% *above* the hand-counted truth, driven by a single ghost-corrupted leaf — so the djvu-based denominators carry leaf-level noise of that order in both directions, and a naive pooled adjustment of the corrected denominator would push the ratio toward ≈ 1.68. That adjusted figure is stated here only to size the noise; it is not a figure, and no ratio in the table is argued away by it. What the second-pass sample does establish — word by word, on three pages spread across the book — is that the English renders the Latin that is actually on the page, neither padded nor thinned; the ratio's height is a property of Acontius's compressed Latin against plain modern English, as it was in Book I, and the sample is the evidence for saying so.

## 3. Seam audit — inter-page sentence carries

All three chunk seams were checked against both chunks' hard-reading logs, and the logs agree on every join:

- **68/69:** the sentence crossing the page turn completes at the end of the earlier section; the later section opens with a new sentence. No duplication, no gap.
- **81/82:** the same, both sides' logs concurring.
- **94/95:** the same, both sides' logs concurring.

Within the chunks, every page-turn carry is logged in the hard-readings list with its disposition — word splits completed whole and counted once where they begin (among them *vtique* across 99→100, confirmed on the images in the second pass), the catchword completion *cala-* / *calamitatesque* across 62→63 (a catchword completion, not a split — corrected by the second pass and recorded in the list's appended updates), and the completion of p. 98's sentence at the head of p. 99, rendered in p. 98's section. The translation file contains no ellipsis characters and no bracketed matter in the text body other than the marginal notes themselves: nothing is silently bridged.

## 4. Second-pass sample — three pages, word by word against the images

Three pages spread across the book were re-read independently, word by word, against the page images, with hand counts taken under the Token-Cleaning Rule as operatively implemented (`count_words.py`):

- **Printed p. 62 (leaf n89): CLEAN.** Hand count **166**, exactly matching the leaf's cleaned djvu count of 166. No material discrepancy — nothing omitted, added, or mistranslated; the logged tentative *quare* construction confirmed in full. Two corrections to hard-reading *notes* (not to the text): the 62→63 carry is a catchword completion, and one sentence's completion belongs to p. 62's section, not p. 63's.
- **Printed p. 80 (leaf n107): CLEAN.** Hand count **180** against the leaf's cleaned djvu **174** — the djvu stream under-reads this leaf by 3.3% and garbles it (the Cicero line "Negabat Scipio" is displaced to the stream's end). No discrepancy of substance: the long Cicero quotation, *hactenus Laelius* correctly outside it, both edge carries, and the blank margins all check. Two note corrections (the quoted reading is *persuasa*, not *persuasas*; one parenthetical is circular as written, its reading right). Counting note: 180 follows the implementation strictly — accented single letters *à*/*è* do not count under it; in substance they would give 182.
- **Printed p. 99 (leaf n126): CLEAN as translation; its machine count DOES NOT RECONCILE.** Hand count **182** against the djvu stream's cleaned **227** — a gap of 45 words that no recount closes, because the stream itself is corrupt on this leaf: the coordinator's direct inspection of the stream shows **57 stream lines for a page of about 33 printed lines**, the surplus being show-through ghost text read off the leaf's verso, and ghost tokens of three or more letters survive the Token-Cleaning Rule and inflate the cleaned count. The hand count governs for this leaf. The translation itself reconciles word by word: nothing omitted, added, or mistranslated; the head lines are p. 98's completion, rendered in p. 98's section as logged; the foot catchword is a catchword only. Two logged readings were ruled on at enlargement and both **confirmed**: *adfurdum* is *adſurdum*, the assimilated spelling of *absurdum* with long *s* (no *b* exists in the word), translated "absurd" correctly; and the 99→100 split is *vtique*, begun *v-* at p. 99's foot and completed *tique* at p. 100's head. One immaterial note: the emphatic particle *quidem* in one clause has no separate English word — emphasis only, no sense lost.

Pooled across the sample: hand counts 528 against djvu cleaned 567 — the machine total runs 7.4% high, entirely on the strength of the one ghost-corrupted leaf; the other two leaves bracket the truth (exact, and 3.3% under). This is the discrepancy that will not reconcile, and its consequence is the caution carried in §2: djvu-based Latin denominators for this volume are estimates with leaf-level noise, in both directions, of up to roughly a quarter on a bad leaf.

## 5. Marginalia carried

**Nine marginal notes** stand in the translation at their places, in the same bracketed form as Book I: pp. 56 (counted to Book II — it stands beside Book II's opening argument below the heading on the shared page), 61, 70, 73, 77, 85, 87, 91, 93. The closing range (pp. 95–100 and the p. 101 completion) carries no marginalia in the print — verified against the images, not merely unlogged — and the two marginal notes standing on the excluded Book III leaves (pp. 102, 104) are named in §1 so they are not lost to the next build.

## 6. Hard readings — consolidated, nothing silently smoothed

**114 entries** across the four chunk lists, consolidated at `work/hard-readings-consolidated2.md`, with the second-pass sample's corrections and confirmations appended beneath the list as dated updates (appended, not written over — Book I's practice). The list's character, as in Book I: print errors translated on the sense with the printed reading named; tentative constructions with the Latin quoted and the tentativeness stated, so any reader can re-judge them; press variants between copies noted where the chunk work caught them; the duplicated printed foliation at leaf n103 (headed "75" in print though the sequence makes it p. 76, the text continuous) recorded in place. Nothing in the list was smoothed into invisibility in the translation: where the English had to choose, the choice and its ground stand in the list.

## 7. Standing and fences

Book II stands as Book I stands: a fresh, complete English translation from the 1631 page images, Acontius credited as author, DRAFT banner standing, delivered into the rebuild folder only. No shelf or clone writes were made; nothing was pushed or uploaded; Book III was not started — though its true opening (mid-p. 101) and its first two marginal notes are now on this record for when it is. The two discrepancies this verification carries openly — the control sheet's Book II/III boundary, wrong by three pages and corrected here on the images' evidence; and p. 99's irreconcilable machine count, explained by the ghost-corrupted stream — are the findings the next stage inherits. Under the house maxim they are not embarrassments to be buried: if a figure can be destroyed by the truth, it deserves to be, and the desk's figures stand only where the pages hold them up.
