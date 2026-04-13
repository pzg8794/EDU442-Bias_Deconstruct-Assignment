# Step 8 — Final LaTeX Transfer Checklist

> **Perplexity draft (draft2).**  
> `step7_draft_with_quotes.md` is the source of truth. This file tracks the transfer of that content into `main.tex`.

---

## Transfer Checklist

### Formatting (APA, 12pt, double-spaced, 1-inch margins)
- [ ] Title page: paper title, your name, course (EDU 442), instructor (Dr. O'Neil-White), date (April 13, 2026)
- [ ] Running header (optional for 5–7 page paper — check if required by syllabus)
- [ ] 12pt font, double spacing, 1-inch margins — all set in `main.tex` preamble
- [ ] Section headers match APA Level 1 format (centered, bold)
- [ ] Block quotes: any quote ≥40 words needs to be indented block format in LaTeX (`\begin{quote}`)
- [ ] No bullet lists in the final paper — convert all bullets in §5 to prose

### Citations (APA in-text)
- [ ] All (Author, Year) citations match the References list
- [ ] Flynn (2024) and Fine et al. (2016) — confirm full journal info before submission
- [ ] Transcript quotes framed as observational data, not citations (no in-text citation needed — frame as "During a grade 4 coding session...") 
- [ ] Seminar quotes framed as "a course instructor noted during a seminar discussion..."

### Content Completeness
- [ ] Introduction — complete ✅
- [ ] Section 1 (Autobiographical) — complete ✅ — Talusan + A1 (seminar) woven in
- [ ] Section 2 (Observation context) — complete ✅
- [ ] Section 3 (Myth vs. Reality) — complete ✅ — Annamma, Flynn, Fine, Bell + B1–B7 quotes
- [ ] Section 4 (Assets) — complete ✅ — Gonzalez, hooks, Paris & Alim + C1–C4 quotes
- [ ] Section 5 (Implications) — complete ✅ — Talusan Ch.7, Nieto, hooks + D1–D3 quotes
- [ ] Section 6 (Conclusion) — complete ✅ — revised paragraph with Annamma closing
- [ ] References — complete ✅ (pending 2 full citations)

### Page Count Check
- Target: **5–7 pages** (body text only, not including title page or references)
- `step7_draft_with_quotes.md` estimated at ~5.5–6 pages when typeset at 12pt double-spaced
- If short: expand the Section 3 structural analysis (Bell/Fine paragraphs) or Section 4 peer-teaching scene
- If long: tighten Section 2 (observation context can be condensed)

### LaTeX-Specific Tasks
- [ ] Paste all section content into `main.tex` sections
- [ ] Format References with `\begin{thebibliography}` or `\bibliography{refs}` + BibTeX
- [ ] Check all special characters (en-dash `--`, ellipsis `\ldots`, italics `\textit{}`)
- [ ] Compile once to check for errors before final submission
- [ ] Export to PDF and do a final read-through

---

## Quick LaTeX Snippet — Block Quote Format

```latex
\begin{quote}
Is this about control or is it about learning? Because I'm asking you for help
with a math assignment---that's about learning. You're shutting us down.
\end{quote}
(Course instructor, pre-service seminar, April 6, 2026)
```

## Quick LaTeX Snippet — APA In-Text Citation

```latex
Annamma et al.\ (2013) describe this as part of the broader apparatus through which schools
label, sort, and punish students (p.~1).
```

---

## Source Material Locations

| What | Where |
|---|---|
| Full revised prose draft | [`draft2/step7_draft_with_quotes.md`](step7_draft_with_quotes.md) |
| All quotes + sources | [`draft2/step4_transcript_quotes.md`](step4_transcript_quotes.md) |
| Full APA references list | [`draft2/step5_citations.md`](step5_citations.md) |
| Transcript source repo | [`pzg8794/teaching-placement` — `teaching_placement_shared`](https://github.com/pzg8794/teaching-placement/tree/teaching_placement_shared/transcripts) |
| Course readings PDFs | [`pzg8794/EDU442 — Course_Readings/`](https://github.com/pzg8794/EDU442/tree/main/Course_Readings) |
| Course reading summaries | [`pzg8794/EDU442 — EDU442-Notes.md §6`](https://github.com/pzg8794/EDU442/blob/main/EDU442-Notes.md) |
| Google Drive course materials | [Shared Course Drive](https://drive.google.com/drive/folders/1BrmUXKHMhgJHcWSNQaW9mTkoaD8sdl8c) |

---

## Status
- [x] Step 7 draft complete and ready
- [ ] Content pasted into main.tex
- [ ] Formatting verified in PDF
- [ ] Flynn + Fine full citations confirmed
- [ ] Final read-through complete
- [ ] Submitted
