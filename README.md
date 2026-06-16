# Bhutan Addressing Guidelines

National addressing documentation for Bhutan, aligned with **ISO 19160** (Parts 1–4).

## Gap analysis presentation (GitHub Pages)

**Live site:** https://nimaytenzin.github.io/bhutan-addressing-guidelines/

PowerPoint-style slide deck (29 slides) covering:
1. **Part 1** — ISO 19160-2 explained (series, Good Practice, Governance, lifecycle)
2. **Part 2** — Gap analysis (executive summary, strengths, gaps, compliance)
3. **Part 3** — Recommendations and roadmap

Navigate with arrow keys · **F** for fullscreen · **Esc** for slide overview.

Also available as `.pptx`: `Bhutan-ISO-19160-2-Gap-Analysis-Presentation.pptx` — regenerate with `python3 scripts/build_presentation.py`

## Repository contents

| Document | Description |
|----------|-------------|
| [BNAIF](Bhutan-National-Addressing-Infrastructure-Framework.md) | Complete national framework — urban + rural |
| [City Guideline](CITY%20ADDRESSING%20GUIDELINE%20PROPOSAL%20FOR%20BHUTAN.md) | Urban Thromde operational manual (source) |
| [Gap Analysis](Bhutan-Addressing-Guideline-ISO-19160-2-Gap-Analysis.md) | ISO 19160-2 conformance assessment |
| [Address Reference System](Bhutan-Address-Reference-System-Proposal.md) | ISO 19160-1 urban profile (superseded by BNAIF §6) |
| [web/](web/) | Interactive HTML report (GitHub Pages) |

## Standards referenced

- ISO 19160-1:2015 — Conceptual model
- ISO 19160-2:2023 — Good practice & governance
- ISO 19160-3:2020 — Data quality
- ISO 19160-4:2023 — Postal addressing / UPU S42
- BSB33:2017 — Road signage (Bhutan)

## Local development

```bash
cd web
python3 -m http.server 8080
# Open http://localhost:8080
```

## Status

Draft for stakeholder consultation — not yet adopted by Royal Government of Bhutan.

**Developed for:** DHS · MoIT · Royal Government of Bhutan
