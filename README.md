<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Lakshya+Dharwal;AI%2FML+Systems+Engineer%2C+Biotech+%26+Health;Builder+%7C+ASU+BME+2026)](https://git.io/typing-svg)

[![Email](https://img.shields.io/badge/ldharwal2003%40gmail.com-000000?style=flat&logo=gmail&logoColor=white)](mailto:ldharwal2003@gmail.com)
&nbsp;
[![SnipGen Live](https://img.shields.io/badge/Live%20Demo-SnipGen-brightgreen?style=flat)](https://snipgen-g4on.vercel.app)
&nbsp;
[![GitHub](https://img.shields.io/badge/github-lakshya--dharwal-181717?style=flat&logo=github)](https://github.com/lakshya-dharwal)

</div>

---

**ABSTRACT**

AI/ML systems engineer building applied machine learning for medicine: genomics, cardiology, oncology, and diagnostic imaging. B.S.E. Biomedical Engineering, Arizona State University, May 2026. Background spans a NASA-affiliated offline diagnostic AI project (provisional patent filed), an ML candidate-review tool used in an active review with a biotech's bioinformatics team, and a deployed drug-repurposing platform. Prior experience in regulated medical device validation (ISO 14971, FDA design controls) informs how these systems get built to survive scrutiny, not just demo well.

---

**STACK**

```
ML / AI          PyTorch · scikit-learn · XGBoost · SHAP · FastAPI · LangGraph · MCP
Data             PTB-XL · cBioPortal · Open Targets · ChEMBL · openFDA · ClinicalTrials.gov
Deployment       Fly.io · Vercel · Supabase · Streamlit
Regulated dev    ISO 14971 · FDA design controls · Pytest · CI/CD (GitHub Actions)
```

---

## Featured Projects

**[1] Atlasonography — offline ultrasound diagnostic AI (Celestia AI)**
*NASA x ASU · PyTorch · UNET · TFLite*

> Offline-capable ultrasound segmentation system built for environments without reliable connectivity, originally scoped for microgravity/space health use cases. The core model, Celestia AI, uses a UNET architecture trained with a hybrid DICE / weighted cross-entropy loss on a 536/135 train/validation split of radiologist-labeled images. **91% sensitivity.** Quantized to **34.2MB** and exported to `.tflite` for on-device inference on a T4 GPU pipeline. Provisional patent filed — code is not public.

---

**[2] SnipGen — CRISPR guide RNA design platform**
*Python · Flask · scikit-learn · GitHub Actions*

> ML on-target scoring model trained on 5,310 real CRISPR screen guides from the Doench 2016 / Azimuth dataset. Spearman correlation on held-out validation: **0.556** (published Azimuth benchmark: ~0.56 to 0.60). CRISPOR genome-wide off-target integration returns real MIT/CFD scores per guide. ClinVar annotation flags off-target hits in clinically significant genes (BRCA2, PTEN, COSMIC tier 1/2). Cloning primers auto-generated for 7 vector systems. Full Pytest suite in CI/CD.

→ [github.com/lakshya-dharwal/snipgen](https://github.com/lakshya-dharwal/snipgen) · [Live demo](https://snipgen-g4on.vercel.app)

---

**[3] Drug Detective — AI drug repurposing platform**
*Python · FastAPI · SSE · GPT-4o-mini*

> Deployed platform that pulls known drug/target/disease data across Open Targets, ChEMBL, PubMed, openFDA, and ClinicalTrials.gov to surface repurposing candidates, with an LLM summary layer over the aggregated evidence. Streams results live via SSE. Benchmarked against 17 known repurposing cases, recovering 5. Built and honestly labeled as a data-integration and retrieval system, not a learned model. The value is in the pipeline: normalizing five inconsistent public APIs into one queryable, explainable surface.

→ [github.com/lakshya-dharwal/drug-detective](https://github.com/lakshya-dharwal/drug-detective) · Live: Fly.io / Vercel

---

## Other Projects

| Project | Status | What it is |
|---|---|---|
| MedAssist Edge | Active | Offline RAG diagnostic assistant for medical device troubleshooting. Corpus audited and rebuilt after 6 of 8 initial sources were found to have zero troubleshooting value; now sourced from FDA MAUDE, IAEA, AAPM, WHO, NHS/HSE. 0.85 distance-threshold retrieval filter, structured DIAGNOSIS/STEPS/EVIDENCE/GAPS output. Isolation Forest anomaly detection: 100% precision, 56% recall at 5% contamination. |
| MTAP Scout | Active | Bladder cancer genomics candidate reviewer. XGBoost + SHAP. Ablation study shows AUC drop from 0.97 to 0.78 when key features removed, evidence the model is learning real signal, not shortcutting. In review with IDEAYA Biosciences' bioinformatics team. |
| CardioTwin | Active | Cardiac digital twin for microgravity applications. ResNet-1D + Transformer on PTB-XL, macro AUROC 0.920. |
| FlexSocket | Pre-prototype | Vacuum-jamming dual-load-path prosthetic socket. Patent-gating phase, developed under ISO 14971 and FDA design control discipline. |
| FDA Pulse | Active | FDA device intelligence platform built on the openFDA API. |
| HeartSignal | Active | Trustworthy ECG classification pipeline. |

---

## MedAssist Edge — full writeup
*Python · Ollama · LangChain · ChromaDB · Streamlit*

- Local inference via Ollama, ChromaDB vector store, zero cloud dependency
- Corpus rebuilt from scratch after auditing and discarding 6 of 8 sources with zero troubleshooting value
- FDA MAUDE failure reports + IAEA, AAPM, WHO, NHS QA standards
- Distance threshold filtering at 0.85, structured DIAGNOSIS / STEPS / EVIDENCE / GAPS output
- Isolation Forest anomaly detection: 100% precision, 56% recall at 5% contamination

→ [github.com/lakshya-dharwal/medassist-edge](https://github.com/lakshya-dharwal/medassist-edge)

---

## Regulated Systems / Validation

*Secondary credibility: the discipline this ML work is built on.*

| Work | Institution | Contribution |
|---|---|---|
| Siemens Giraffe X-ray validation | EPICS / Project C.U.R.E. | LabVIEW validation protocols, pass/fail criteria, regulatory documentation |
| Broadband research tools QA | ASU NextLab | Sprint-embedded testing, backlog grooming, defect reporting in Agile structure |
| ECG multilabel classification | ASU BME 494 Capstone | Evaluation framework across 12 cardiac conditions: AUROC, F1, SHAP interpretability |

---

<div align="center">

**Open to AI/ML Systems Engineer roles in biotech and health.**
`ldharwal2003@gmail.com` · [github.com/lakshya-dharwal](https://github.com/lakshya-dharwal) · [SnipGen live demo](https://snipgen-g4on.vercel.app)

</div>
