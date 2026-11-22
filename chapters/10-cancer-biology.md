# 10 · Cancer Biology & Precision Oncology

[← Genomics & Bioinformatics](09-genomics-bioinformatics.md) · [Contents](../README.md)

> **In one line:** cancer is a disease of the genome — cells accumulate changes that let them grow without limits, escape control and spread.

## 1. The hallmarks of cancer

Hanahan & Weinberg (2000, 2011, updated 2022) described the capabilities cells acquire on the way to cancer:

| Hallmark | In plain words |
|:--|:--|
| Sustaining proliferative signalling | Accelerator stuck on |
| Evading growth suppressors | Brakes cut |
| Resisting cell death | Ignores apoptosis |
| Enabling replicative immortality | Telomerase switched on |
| Inducing angiogenesis | Builds its own blood supply |
| Activating invasion & metastasis | Spreads |
| Reprogramming energy metabolism | Warburg effect — aerobic glycolysis |
| Avoiding immune destruction | Hides from T cells (e.g. PD-L1) |
| **Enablers:** genome instability; tumour-promoting inflammation | |
| **2022 additions:** phenotypic plasticity, non-mutational epigenetic reprogramming, polymorphic microbiomes, senescent cells | |

## 2. Oncogenes vs tumour suppressors

| | Oncogene | Tumour-suppressor gene |
|:--|:--|:--|
| Normal version | Proto-oncogene (growth promoter) | Growth restrainer / genome guardian |
| Change | Gain of function | Loss of function |
| Alleles hit | One is enough (dominant) | Usually both (**Knudson's two-hit**) |
| Examples | *KRAS*, *MYC*, *HER2/ERBB2*, *EGFR*, *BCR-ABL1* | *TP53*, *RB1*, *BRCA1/2*, *APC*, *PTEN* |

*TP53* is the most frequently mutated gene across human cancers — "guardian of the genome".

## 3. From normal cell to metastasis

```mermaid
flowchart LR
  N[Normal cell] -->|1st hit| H[Hyperplasia]
  H -->|more mutations| D[Dysplasia]
  D --> CIS[Carcinoma in situ]
  CIS -->|invades basement membrane| I[Invasive cancer]
  I -->|EMT · intravasation · circulation| M[Metastasis]
```

The **Vogelstein model** of colorectal cancer: *APC* → *KRAS* → *TP53* (with other events) across adenoma → carcinoma.

## 4. Causes

| Class | Examples |
|:--|:--|
| Chemical carcinogens | Tobacco smoke (benzo[a]pyrene), aflatoxin B1, asbestos |
| Radiation | UV (thymine dimers → melanoma), ionising radiation |
| Infections | HPV (cervical, via E6 → p53 and E7 → Rb), HBV/HCV (liver), EBV, *H. pylori* (gastric) |
| Inherited | *BRCA1/2* (breast/ovarian), Lynch syndrome (MMR genes), Li-Fraumeni (*TP53*) |
| Lifestyle | Alcohol, obesity, physical inactivity |

## 5. Diagnosis

Imaging (CT, MRI, PET) · histopathology and **immunohistochemistry** (ER, PR, HER2) · tumour markers (PSA, CA-125, AFP, CEA) · **next-generation sequencing panels** · **liquid biopsy** (circulating tumour DNA) · TNM staging.

## 6. Treatment — from blunt to precise

| Approach | How it works | Examples |
|:--|:--|:--|
| Surgery | Removes the tumour | Mastectomy, resection |
| Radiotherapy | DNA damage | External beam, brachytherapy |
| Chemotherapy | Kills dividing cells | Cisplatin, paclitaxel, 5-FU |
| **Targeted therapy** | Blocks a specific driver | Imatinib (BCR-ABL1, CML) · trastuzumab (HER2) · osimertinib (EGFR) · vemurafenib (BRAF V600E) |
| Synthetic lethality | Exploits a repair defect | PARP inhibitors (olaparib) in *BRCA*-mutant cancers |
| **Immunotherapy** | Unleashes T cells | Anti-PD-1 (pembrolizumab, nivolumab), anti-CTLA-4 (ipilimumab), CAR-T (CD19) |
| Hormone therapy | Starves hormone-driven tumours | Tamoxifen, aromatase inhibitors, androgen deprivation |

**Tumour-agnostic approvals** treat by biomarker, not organ — e.g. checkpoint inhibitors for MSI-high/dMMR tumours, larotrectinib for *NTRK* fusions.

## 7. Big data in cancer

- [The Cancer Genome Atlas (TCGA)](https://portal.gdc.cancer.gov) — 33 cancer types, multi-omics.
- [cBioPortal](https://www.cbioportal.org) — explore mutations, survival and expression interactively.
- [COSMIC](https://cancer.sanger.ac.uk/cosmic) — somatic mutation catalogue and **mutational signatures** (e.g. SBS4 tobacco, SBS7 UV).
- [OncoKB](https://www.oncokb.org) — which mutations are clinically actionable.

## ⚠️ Common confusions

- "Cancer gene" usually means a mutated *normal* gene, not a foreign one.
- Inherited *BRCA* mutation = one hit already present; cancer still needs a second hit.
- Benign tumours don't invade or metastasise — but can still be dangerous by location.

## 📝 Practice

1. Knudson's two-hit hypothesis was based on: (a) breast cancer (b) retinoblastoma (c) CML (d) melanoma
2. Imatinib targets: (a) HER2 (b) EGFR (c) BCR-ABL1 (d) PD-1
3. PARP inhibitors work best in tumours with defective: (a) mismatch repair (b) homologous recombination (c) NHEJ (d) base excision
4. HPV E6 protein promotes degradation of: (a) Rb (b) p53 (c) MYC (d) KRAS
5. Which is a tumour-suppressor gene? (a) *KRAS* (b) *MYC* (c) *APC* (d) *HER2*

<details><summary><b>Answers</b></summary>

1 (b) · 2 (c) · 3 (b) · 4 (b) · 5 (c)
</details>

## 📖 Go deeper

- [Hanahan, *Hallmarks of Cancer: New Dimensions* (Cancer Discovery, 2022)](https://doi.org/10.1158/2159-8290.CD-21-1059)
- [National Cancer Institute — Cancer biology](https://www.cancer.gov/about-cancer/understanding/what-is-cancer)
- [Coursera — Understanding Cancer Metastasis (Johns Hopkins)](https://www.coursera.org/learn/cancer-metastasis)
