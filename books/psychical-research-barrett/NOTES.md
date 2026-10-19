# Psychical Research (Barrett, 1911) — Edition Notes (Rare & Obscure Books)

BASIS sentence (line 1 of draft.md / Basis line of book.md): Clean reading edition of W. F. Barrett's Psychical Research (Home University Library, 1911; Internet Archive psychicalresear00barr); spelling and wording original; running headers, page numbers and scanner noise removed.

## Source — validation

- Sole source: `sources/barrett-1911-psychical-research_djvu.txt` (436,899 bytes; 10,596 lines), the Internet Archive djvu text of item `psychicalresear00barr`.
- Title page as scanned (djvu lines 103–135): PSYCHICAL RESEARCH / BY / W. F. BARRETT, F.R.S. / Professor of Experimental Physics in the Royal College of Science for Ireland, 1873–1910 / NEW YORK HENRY HOLT AND COMPANY / LONDON WILLIAMS AND NORGATE. Series furniture (djvu lines 1–102) identifies it as Home University Library of Modern Knowledge No. 24 (editors Herbert Fisher, Gilbert Murray, J. Arthur Thomson, William T. Brewster; list entry "PSYCHICAL RESEARCH .... By W. F. Barrett"). Preface signed W. F. Barrett, Kingston, Co. Dublin, August 1911. This is the commissioned work; no other work is packaged here.
- Contents as scanned (djvu lines 194–286): Preface (v); I Science and Superstition (9); II Unconscious Muscular Action. The Pendule Explorateur — Autoscopes (20); III The Society for Psychical Research — Human Personality (32); IV The "Willing Game" and So-called Thought-reading (44); V Thought-transference in the Normal State of the Percipient (52); VI Thought-transference in the Hypnotic State (70); VII Mesmerism — Hypnotism — Suggestion (82); VIII Experimental and Spontaneous Telepathy over Long Distances (96); IX Visual Hallucinations: Phantasms of the Living and Dead (111); X Dreams and Crystal-visions (133); XI Supernormal Perception: Seeing without Eyes (151); XII The So-called Divining- or Dowsing-rod (167); XIII Hauntings and Poltergeists (187); XIV The Physical Phenomena of Spiritualism (211); XV Automatic Writing. Cross-correspondence (219); XVI Automatic Writing (continued). Survival after Death (236); Bibliography (249); Index (253). All sixteen chapters, the Preface and the Bibliography are present in the scan and are reproduced; the Index is not (see below).

## What this edition is

A clean reading edition of Barrett's 1911 survey of the Society for Psychical Research's work — Barrett's own outline, in his own wording, from unconscious muscular action and telepathy through apparitions, hauntings and automatic writing to the survival evidence. Nothing has been modernized, summarized or rewritten; this is a reprint, not the editor's research.

## How the text was cleaned

- Bounds: the edition runs from the title page through the end of the Bibliography. Excluded: the publisher's Home University Library list/ads at the head of the scan (djvu lines 1–102), the Internet Archive digitization leaf, and the publisher's catalogue, University of British Columbia due-date slip and barcode at the tail. The Index (original pp. 253–end) is omitted: it is a page-number finder keyed to the 1911 pagination, which this repaginated edition does not preserve; it remains available in the source scan. Contents retains an "Index [not reproduced]" line so the book's structure is honestly shown.
- Running heads, folios and page numbers stripped throughout (e.g. "10 PSYCHICAL RESEARCH", "SCIENCE AND SUPERSTITION 11", "UNCONSCIOUS MUSCULAR ACTION 21", "DIVINING- OR DOWSING-ROD 169", standalone numerals and roman folios, the signature "F 2"). Sentences split across page turns were rejoined; no words were added.
- Chapter headings converted to Markdown `## `, in the form "Chapter II. Unconscious Muscular Action. The Pendule Explorateur — Autoscopes", with titles title-cased from the printed Contents/headings. Preface, Contents and Bibliography likewise headed `## `.
- Line-break hyphens rejoined (e.g. super-/stition → superstition); true compounds kept their hyphen (divining-rod, thought-transference, cross-correspondence, so-called). OCR spacing before punctuation ( ; : , . ? !) closed up and "' s" possessives rejoined. The djvu double-spacing between words collapsed and OCR lines joined into paragraphs.
- Contents rebuilt as a clean list with the original 1911 page numbers retained for reference; the scan's two-column Contents (chapter titles and page numbers in separate blocks) was re-paired from the printed list.
- Scanner-garbage fixes (obvious misread glyphs only, each of the letter-for-letter kind): SCIEXCE → SCIENCE, DEEAMS → DREAMS, AUTOS COPES → AUTOSCOPES, PYSCHICAL → PSYCHICAL, SUPERNORIVIAL → SUPERNORMAL, DOAYSING → DOWSING, Kingstoivn → Kingston, Dublin^ → Dublin, Revice → Revue, pubhshed → published, w^e → we, ^vith/^Vhat → with/What, s^^^ft → swift. Title-page imprint punctuation normalized in the draft's title block ("NEW YORK: HENRY HOLT AND COMPANY" etc.).

## Doubtful places — kept honest, nothing invented

- Chapter XI heading: the scan heads the eleventh chapter "CHAPTER X" a second time (djvu line 5689; the Contents correctly lists XI Supernormal Perception at p. 151). Headed "Chapter XI" in this edition and logged here; not silent.
- Body OCR letter-errors beyond the classes above were corrected only where the intended reading is certain; scattered single-letter misreads that survive proofing may remain (e.g. the French "pratiques super stitieuses" spacing inside Ch. II's Le Brun title). Readers citing a single word or a French title should check the scan image. Barrett's spelling and wording otherwise stand — "endeavoured", "sceptics", period forms kept; nothing modernized.
- Quotation spacing follows the cleanup above (spaces before closing quotes closed where the OCR spaced them); no quotation wording was altered.
- Figures/illustrations: none are reproduced; the text's figure references, where any occur, stand as printed. (No plate list is printed in this volume.)

## Word count

`wc -w` on `books/psychical-research-barrett/draft.md`: **58102** words (basis line, title block, Preface, Contents, Chapters I–XVI, Bibliography). metadata.json `word_count` carries this draft count.

## Rendering

No pandoc is installed; the PDF was set with Python reportlab (6×9 in page, 432×648 pt, Times-Roman serif, title page first, page numbers at bottom centre) and the EPUB hand-built as EPUB 3 (mimetype / OPF / XHTML nav + one XHTML file per `## ` section, headings as h2); the .txt is the title page plus body with Markdown marks removed. Files: book.md, draft.md, NOTES.md, metadata.json, psychical-research-barrett.pdf, psychical-research-barrett.txt, psychical-research-barrett.epub. No upload made; upload is the parent step.

## Rights

1911 source text is public domain. Edition rights wording UNRULED — see metadata.json rights_flag: PARENT RULING NEEDED (CC0 vs (c) editor, free redistribution). No upload made; upload is a parent step.
