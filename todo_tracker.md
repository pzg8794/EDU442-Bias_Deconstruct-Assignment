# TODO — Deconstructing Bias (Canonical Tracker)

This is the single TODO tracker for finishing the paper using the **root-level canonical files**.

**Important:** `draft1/` and `draft2/` are still preserved for review and source-checking. Do not delete drafts until you approve the final docs.

## Canonical files (what we keep)

- Requirements: `REQUIREMENTS.md`
- Paper source (LaTeX): `main.tex`
- Compile output (local): `main.pdf`

## Status snapshot (best-of-both)

- [x] Topic and scope finalized
- [x] Bias focus finalized
- [x] Observation work documented
- [x] Best-of-both drafts merged into a submission-ready `main.tex`
- [x] Missing references resolved (Fine, Flynn)
- [x] Root-level PDF compiled from `main.tex`

## Final checks (finish + review)

- [ ] Page count check against the assignment requirement (5–7 pages body; confirm what counts per instructor/syllabus)
- [ ] APA-ish formatting check: 12pt, 1-inch margins, double-spaced, paginated, centered bold headings
- [ ] Quote formatting check: any quote ≥ 40 words converted to a LaTeX block quote (`\begin{quote}...\end{quote}`)
- [ ] Proofread the compiled PDF for clarity, flow, and small errors

## Compile

- `latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex`

## Submission

- [ ] Export final PDF and submit to Blackboard

## If needed (only if you want to push)

- [ ] `git status` is clean in the assignment repo
- [ ] Changes committed/pushed in the assignment repo
- [ ] Submodule pointer updated/committed in the EDU442 superproject
