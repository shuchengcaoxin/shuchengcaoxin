<p align="center">
  <img src="assets/hero.svg" width="100%" alt="Shucheng Cao, also known as Bangli Cao, a PhD researcher in causal genetics and research software" />
</p>

<p align="center">
  <a href="https://shuchengcaoxin.github.io/">Website</a> ·
  <a href="https://scholar.google.com/citations?user=q1cAyE0AAAAJ&hl=en">Google Scholar</a> ·
  <a href="https://orcid.org/0000-0002-9115-6259">ORCID</a> ·
  <a href="https://www.linkedin.com/in/shucheng-bangli-cao/">LinkedIn</a> ·
  <a href="mailto:shucheng.cao@mail.mcgill.ca">Email</a>
</p>

<p align="center">
  <strong>Open to opportunities</strong><br />
  Graduating in 2027; available for 2026–27 internships and 2027 full-time roles.
</p>

I’m **Shucheng Cao**, also known and published as **Bangli Cao** (曹书诚), a PhD candidate in Quantitative Life Sciences at McGill University.

I study whether circulating proteins contribute causally to obesity and metabolic liver disease. Most of my work uses Mendelian randomization, colocalization, and large-scale GWAS and pQTL data. I also build research software when the evidence trail is difficult to inspect.

> **Research question** — Which circulating proteins change metabolic disease risk?
>
> **Evidence standard** — Replication across independent pQTL platforms, followed by colocalization and sensitivity checks.
>
> **What I build** — Pipelines and evidence tools that record what entered, what survived, and why a step was skipped.

## Current work

### Proteome-wide causal genetics

My PhD research screens circulating proteins for causal effects on metabolic liver disease and obesity. A candidate has to reproduce across two independent proteomic platforms and survive colocalization and sensitivity checks before I take it seriously.

### [CausalSentinel / OpenCausal](https://github.com/ds4cabs/CausalSentinel)

I led the engineering for this CABS 2026 team project. The system joins published MR estimates with evidence from eight downstream public biomedical databases, while keeping the source evidence alongside every result.

**991 protein dossiers** · **101,543 retrieved MR estimates** · **9 public data sources**

<p align="center">
  <img src="assets/opencausal-flow.svg" width="100%" alt="Published MR estimates and public databases are stored in an evidence ledger, rendered by code, and checked by a validation gate" />
</p>

The final page is rendered from a structured ledger. If model-written prose contradicts the retrieved evidence, the card is marked as failed rather than quietly published.

<p align="center">
  <a href="https://ds4cabs.github.io/CausalSentinel/viewer/">
    <img src="assets/opencausal-card.png" width="94%" alt="An OpenCausal evidence card showing retrieved MR and clinical-development evidence" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ds4cabs/CausalSentinel">Repository</a> ·
  <a href="https://ds4cabs.github.io/CausalSentinel/dossiers/">Browse dossiers</a> ·
  <a href="https://ds4cabs.github.io/CausalSentinel/viewer/">Open card viewer</a>
</p>

## Selected work

- **AbdomenCT-1K** — helped build and evaluate a public multi-centre abdominal CT benchmark with more than 1,000 scans from 12 hospitals; published in *IEEE Transactions on Pattern Analysis and Machine Intelligence* (2022). [Paper](https://doi.org/10.1109/TPAMI.2021.3100536)
- **Proteome-wide causal inference for metabolic liver disease** — presented at ESHG 2026; manuscript in revision.
- **Ultrashort peptide self-assembly** — used molecular dynamics to study the physical drivers of assembly during my MSc at KAUST.

## How I work

I care about whether an analysis can still be checked months later: which data entered, which variants survived each step, and why a result was skipped. That preference shapes both my genetics pipelines and the research tools I build.

**Methods:** Mendelian randomization · colocalization · GWAS and pQTL analysis · R · Python · Linux/HPC
