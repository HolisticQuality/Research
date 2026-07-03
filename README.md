# Holistic Quality — Research

Public, citable research artifacts published by **Holistic Quality LLC**. Each item is an **AI-assisted, human-verified evidence synthesis**: every quantitative claim and citation is checked against its published primary source, and `sources/index.json` links each citation to its publisher record and an archived snapshot so any reader (or regulator) can verify the work independently.

> **Not peer-reviewed.** These are self-published working papers. They have not undergone formal peer review.
>
> **Not medical advice.** These syntheses summarize the state of the published scientific literature. They are **not** medical advice — do not use them to diagnose, treat, or make personal health decisions. Consult a qualified clinician.
>
> **Association ≠ causation.** Where the evidence is contested, or where an association does not establish causation, the papers state so explicitly.

## License

Everything in this repository — the papers (`papers/`), the figures (`figures/*.svg`), the figure data (`figures/figures-data.json`), and the citation manifest (`sources/index.json`) — is **Holistic Quality's own work or factual citation metadata**, licensed under [**Creative Commons Attribution 4.0 International (CC BY 4.0)**](https://creativecommons.org/licenses/by/4.0/); see [`LICENSE`](LICENSE) for the full legal code. You are free to share and adapt it for any purpose, including commercially, provided you give appropriate credit. (This matches the license of the corresponding Zenodo deposit.)

The **primary sources** the papers cite are third-party copyrighted works; they are **not** re-hosted here. `sources/index.json` links to each publisher's canonical record (DOI/PMID) and to an archived snapshot served at `holisticquality.io/receipts` for link-rot protection. All rights in those sources remain with their respective publishers.

## Contents

| Path | What |
|---|---|
| [`papers/particulate-matter-and-alzheimers-full.md`](papers/particulate-matter-and-alzheimers-full.md) | Full evidence review — PM2.5 and Alzheimer's disease (the citable version of record) |
| [`papers/particulate-matter-and-alzheimers.md`](papers/particulate-matter-and-alzheimers.md) | Summary brief of the above |
| [`papers/microplastics-and-the-human-body-full.md`](papers/microplastics-and-the-human-body-full.md) | Full evidence review — microplastics and the human body (the citable version of record) |
| [`papers/microplastics-and-the-human-body.md`](papers/microplastics-and-the-human-body.md) | Summary brief of the above |
| [`papers/pfas-body-burden-full.md`](papers/pfas-body-burden-full.md) | Full evidence review — PFAS body burden and the uneven distribution of industrial chemical exposure (the citable version of record) |
| [`papers/pfas-body-burden.md`](papers/pfas-body-burden.md) | Summary brief of the above |
| [`figures/`](figures/) | The three PM&A report figures (SVG) + `figures-data.json` (the sourced values each figure renders); the microplastics and PFAS reports carry no figures |
| [`sources/index.json`](sources/index.json) | Citation manifest — each cited source's title, DOI/PMID, publisher URL, and an archived-snapshot URL (on holisticquality.io, with SHA-256) for verification and link-rot protection |

## How to cite

Each full report is a separately citable Zenodo deposit:

> Robey, L. (2026). *Particulate Matter and Alzheimer's Disease: Associations, Mechanisms, and Missing Links* (full evidence review, Version 1.0). Holistic Quality LLC. https://doi.org/10.5281/zenodo.21109168
>
> Robey, L. (2026). *Microplastics and the Human Body: Exposure, Translocation, and the Margin-of-Exposure Question* (full evidence review, Version 1.0). Holistic Quality LLC. https://doi.org/10.5281/zenodo.21172814
>
> Robey, L. (2026). *PFAS Body Burden and the Uneven Distribution of Industrial Chemical Exposure* (full evidence review, Version 1.0). Holistic Quality LLC. https://doi.org/10.5281/zenodo.21181282

Each version DOI is frozen to its v1.0; each deposit also carries a version-independent concept DOI that always resolves to the latest version (PM&A [10.5281/zenodo.21109167](https://doi.org/10.5281/zenodo.21109167), microplastics [10.5281/zenodo.21172813](https://doi.org/10.5281/zenodo.21172813), PFAS [10.5281/zenodo.21181281](https://doi.org/10.5281/zenodo.21181281)). The reports are also published at [holisticquality.io/research](https://holisticquality.io/research).

## Provenance

These files are the published mirror of the verified source maintained by Holistic Quality LLC. The canonical cited version is pinned to a release tag (e.g. `v1.1`) so the referenced version is immutable; `main` may advance.
