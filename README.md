# ICTP 2026 Paper – HPDC Aluminum Alloy

## Purpose
This repository manages the abstract and full paper for ICTP 2026.
- Writing and version control are done in LaTeX.
- Official submission is done in Word (DOCX) format.

## Directory Structure
- `tex/`  
  LaTeX source files (single source of truth for content).

- `submission/`  
  Submission-ready Word files formatted using ICTP templates.
  - `abstract/` : abstract DOCX
  - `paper/` : full paper DOCX

- `templates/`  
  Official ICTP Word templates (do not edit).

- `figures/`  
  Figures used in the paper.

- `bib/`  
  Bibliography files (`.bib`).

- `build/`  
  LaTeX build artifacts (ignored by Git).

## Workflow
1. Write and revise content in LaTeX (`tex/`).
2. Commit LaTeX changes frequently.
3. Before submission, transfer finalized content to Word templates.
4. Store submission-ready DOCX files in `submission/`.
5. Commit submission versions separately.

## Notes
- `tex/` is the content source of truth.
- `submission/` contains final, formatted files for upload.
