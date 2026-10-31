# Karnataka Electoral Roll Intelligence | SIR 2026

An editorial, high-performance demographic and electoral roll revision observatory for the state of Karnataka, India. Based on 45,643,915 registered electors across all 224 Assembly Constituencies from the 2026 Special Intensive Revision (SIR).

## 🚀 Hosted on GitHub Pages
This repository contains a zero-dependency static build inside `/docs` that runs completely client-side with sub-millisecond filtering, sorting, and charts.

### Enabling GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** &rarr; **Pages** (in the left sidebar).
3. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/docs`
4. Click **Save**.
5. Your dashboard will be live at `https://<your-username>.github.io/<repo-name>/` in ~30 seconds.

---

## 📊 Features & Analytics
- **Executive Demographic Briefing**: Total registered electors, sex ratio parity, age pulse, and roll churn.
- **District Observatory**: Youngest districts (lowest mean age & highest Gen Z voter share), oldest senior districts, gender parity comparisons, and roll turnover.
- **Assembly Constituencies Directory (224 Seats)**: Full multi-column sorting (Asc/Desc) by name, size, sex ratio, mean age, youth share, and roll revision volume.
- **Data Quality & OCR Audit**: OCR confidence scores, missing fields, and flagged record rates across all 224 seats.
- **Instant Client-Side CSV Export**: One-click download of constituency metrics directly from the browser.
- **Embedded Methodology Guide & Citation**: Field guide explaining roll revision mechanics, spatial geographies, and formal CFF / BibTeX citation data.

---

## 📚 Dataset Citation & Provenance
If you use this dataset or observatory in research, news reports, or publications, cite it as below:

```yaml
cff-version: 1.2.0
message: "If you use this dataset, cite it as below."
title: "Karnataka SIR 2026 voter rolls: de-identified electoral roll dataset"
type: dataset
version: "2026-10-28-statewide.3"
date-released: "2026-10-29"
authors:
  - name: "Diagram Chasing"
    website: "https://sir.diagramchasing.fun"
url: "https://sir.diagramchasing.fun"
repository-code: "https://github.com/diagramchasing/karnataka-sir-voter-rolls-data"
license: ODbL-1.0
abstract: "Every entry in Karnataka's final electoral roll from the 2026 Special Intensive Revision (English edition, revision 1), for all 224 assembly constituencies. Diagram Chasing processed the Election Commission of India's PDFs with OCR, removed names, relatives' names, house numbers and voter IDs, and added summary tables. 45,643,915 entries across 60,923 parts."
keywords:
  - electoral roll
  - Karnataka
  - India
  - Election Commission of India
  - Special Intensive Revision
  - open data
references:
  - type: data
    title: "Final electoral roll, Special Intensive Revision 2026, Karnataka"
    authors:
      - name: "Election Commission of India"
    url: "https://voters.eci.gov.in/download-eroll?stateCode=S10"
```

### BibTeX
```bibtex
@dataset{diagramchasing_karnataka_sir_2026,
  author    = {{Diagram Chasing}},
  title     = {Karnataka SIR 2026 voter rolls: de-identified electoral roll dataset},
  year      = {2026},
  version   = {2026-10-28-statewide.3},
  publisher = {Diagram Chasing},
  url       = {https://sir.diagramchasing.fun}
}
```
