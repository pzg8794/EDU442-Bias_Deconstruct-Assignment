# Draft 2 (Canonical)

This folder is the single working drive for the Deconstructing Bias paper.

## Use these three files

- `REQUIREMENTS.md` — assignment prompt, rubric, and formatting requirements
- `todo_tracker.md` — the single tracker for final checks + submission
- `main.tex` — the submission-ready paper (LaTeX)

## Compile

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

Output: `main.pdf`
