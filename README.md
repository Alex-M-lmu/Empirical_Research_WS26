# Empirical Research in Accounting, Auditing and Capital Markets — Tutorial

LMU Munich · Institute for Accounting, Auditing and Analysis · Winter semester 2026/27
Tutorials: Dr. Jan Seitz (jan.seitz@lmu.de) · Room 316 and Zoom

This repository contains the slides and R Markdown documents for the tutorial.
Organising question: **How do I know that this analysis is correct and informative?**

## Getting started (once)

1. Install R, RStudio and Git (see slides of Tutorial 1, block IV).
2. **Fork** this repository (button top right) → you get your own copy.
3. In RStudio: *File → New Project → Version Control → Git* → paste the URL of **your fork**.
4. Copy the data files from Moodle into `data/` (see `data/README.md`).
5. Open `session_01/Session_01_student.Rmd` and knit it.

## Every session

1. On github.com, in your fork: **Sync fork → Update branch** (gets new material).
2. In RStudio: **Pull** (blue arrow).
3. Work in the `Session_XX_student.Rmd` of the session.
4. **Commit** with a clear message, then **Push** (green arrow).

## Structure

| Folder | Content |
|--------|---------|
| `EmpRes-Tutorial.Rproj` | Open this file to open the project |
| `data/` | Raw data from Moodle (not on GitHub, read-only) |
| `session_01/` … `session_05/` | Slides (PDF) and R Markdown per tutorial |
| `output/` | Everything the code creates (not on GitHub) |

## Schedule

| Date | Tutorial |
|------|----------|
| Thu 22 Oct 2026 | 1 · Reproducible research workflow |
| Thu 29 Oct 2026 | 2 · Data preparation and verification |
| Thu 5 Nov 2026 | 3 · Measurement and construct validity |
| Thu 26 Nov 2026 | 4 · Causal inference in practice |
| Fri 27 Nov 2026 | 5 · Lab workshop |

## Rules

- Never commit licensed data, personal data or tokens (see `.gitignore`).
- Use relative paths with `here::here()`, never `C:/Users/...`.
- Check AI-generated code independently before you use it.
