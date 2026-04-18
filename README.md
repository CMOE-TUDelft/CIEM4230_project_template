# CIEM4230 Project Report Template

Template repository for the TU Delft course **CIEM4230: Floating and Submerged Structures**.

This project provides a LaTeX report structure for the course project, including chapter files, appendices, and guidance placeholders for evidence-driven engineering reporting.

## Repository Structure

- `main.tex`: Main report document and chapter include order
- `style.tex`: Shared formatting and custom commands
- `chapters/01_design_basis_metocean.tex`
- `chapters/02_concept_lifecycle.tex`
- `chapters/03_mooring_design.tex`
- `chapters/04_numerical_modelling.tex`
- `chapters/05_probabilistic_assessment.tex`
- `chapters/06_stakeholders_ethics.tex`
- `chapters/07_concept_evaluation.tex`

## Build

Compile from the repository root:

```bash
latexmk -pdf main.tex
```

Clean intermediate files:

```bash
latexmk -c
```

## Usage Notes

- Keep the main report within **25-35 pages**.
- Move long derivations, raw outputs, and extended code to appendices.
- Replace all placeholder text before submission.
- Ensure claims are supported by figures, tables, calculations, or references.

## AI Use in This Template

- The report includes:
  - A **Written Statement** on restricted AI use in the "How to Use This Template" section.
  - A mandatory **In-depth Acknowledgement of AI Use** section at the end of the document.
- Students remain fully responsible for all submitted content.
