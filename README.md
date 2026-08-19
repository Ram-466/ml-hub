<h1 align="center">ML Hub</h1>

<p align="center">
  <b>Bhargava Ram</b> — Machine Learning Engineer in the making<br>
  MS Business Analytics, Trine University
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square" alt="XGBoost">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
</p>

<p align="center">
  <i>The index for everything I build and study — roadmap, notes, and projects in one place.</i>
</p>

---

## Start here

The three projects that best represent what I can do:

| Project | What it does | Stack | Result |
|---|---|---|---|
| **[duplicate-question-detector](https://github.com/Ram-466/duplicate-question-detector)** | Predicts whether two questions are semantic duplicates, on ~400k Quora pairs. Hand-crafted similarity features instead of black-box embeddings. | TF-IDF · RapidFuzz · Logistic Regression · XGBoost | **0.748 accuracy / 0.834 ROC-AUC** on 40,428 validation pairs — XGBoost beats the linear baseline on every metric |
| **[esrgan-plus](https://github.com/Ram-466/esrgan-plus)** | 4× image super-resolution. Adds Squeeze-and-Excitation channel attention inside each RRDB block, fine-tuned from official Real-ESRGAN weights. | PyTorch · GAN · VGG perceptual loss · RaGAN | Full training + benchmark pipeline built; PSNR/SSIM run on Set5/Set14/BSD100 pending GPU |
| **[pdf-exam-notes](https://github.com/Ram-466/pdf-exam-notes)** | Turns an uploaded PDF into bullet summaries, definitions, and likely exam questions. Local-first, no database. | FastAPI · Uvicorn · pdfplumber · Vanilla JS | Working end-to-end app with a served API and downloadable output |

> On `esrgan-plus`: that results table reports measured numbers only. Benchmarks stay marked pending until the GPU run actually produces them — no projected figures.

---

## Notes

One repo per phase. Each holds `notes/` for concepts and `snippets/` for runnable code.

| # | Topic | Repo | Status |
|---|---|---|---|
| 1 | Python for ML | [ml-notes-python](https://github.com/Ram-466/ml-notes-python) | 🔄 In progress |
| 2 | Math & Statistics | [ml-notes-math-stats](https://github.com/Ram-466/ml-notes-math-stats) | ⬜ Queued |
| 3 | Data & EDA | [ml-notes-data](https://github.com/Ram-466/ml-notes-data) | 🔄 In progress |
| 4 | Core Machine Learning | [ml-notes-ml](https://github.com/Ram-466/ml-notes-ml) | ⬜ Queued |
| 5 | Deep Learning | [ml-notes-deep-learning](https://github.com/Ram-466/ml-notes-deep-learning) | ⬜ Queued |
| 6 | NLP | [ml-notes-nlp](https://github.com/Ram-466/ml-notes-nlp) | ⬜ Queued |
| 7 | MLOps & Deployment | [ml-notes-mlops](https://github.com/Ram-466/ml-notes-mlops) | ⬜ Queued |

---

## Roadmap progress

Full detail: **[ml-roadmap](https://github.com/Ram-466/ml-roadmap)**

| Phase | Notes | Applied in a project |
|---|---|---|
| 0 · Setup & Foundations | ✅ | Git workflow, environments, and repo structure in use across this hub |
| 1 · Python for ML | 🔄 | Every project here |
| 2 · Math & Statistics | ⬜ | — |
| 3 · Data Handling & EDA | 🔄 | `duplicate-question-detector` — EDA notebook over a 400k-row pipeline |
| 4 · Core Machine Learning | ⬜ | ✅ `duplicate-question-detector` — feature engineering, LR vs XGBoost, full metric suite |
| 5 · Deep Learning | ⬜ | ✅ `esrgan-plus` — RRDBNet + SE-attention, GAN training loop, transfer learning from pretrained weights |
| 6 · NLP | ⬜ | ✅ `duplicate-question-detector` — preprocessing, TF-IDF, similarity features |
| 7 · MLOps & Deployment | ⬜ | 🔄 `pdf-exam-notes` — FastAPI service + frontend; Docker and CI/CD still to come |
| 8 · Portfolio Projects | — | 🔄 3 of 4 target types shipped: classic ML ✅ · NLP ✅ · CV ✅ · deployed end-to-end 🔄 |

**Reading this table:** the notes lag the projects on purpose. I build first and write the concept up afterwards, so a ⬜ next to a ✅ means the work is done and the write-up is the part still owed.

---

## What I'm focused on now

- Filling in the Core ML and Deep Learning notes behind projects already shipped
- Running the `esrgan-plus` benchmark on a GPU and publishing the real PSNR/SSIM numbers
- Taking one project fully end-to-end: Docker + CI/CD + a deployed, monitored endpoint

---

## Tech

**Languages** · Python · SQL · JavaScript · HTML/CSS
**ML** · scikit-learn · XGBoost · PyTorch · NumPy · Pandas · Matplotlib
**NLP** · TF-IDF · RapidFuzz · Transformers
**Serving** · FastAPI · Uvicorn
**Tooling** · Git · GitHub · Jupyter · VS Code · Google Colab

---

## Other work

- [hair-care-consultation](https://github.com/Ram-466/hair-care-consultation) — frontend project generating personalized routines
- [ML-checkbox](https://github.com/Ram-466/ML-checkbox) — study tracker
- [Ram-466.github.io](https://github.com/Ram-466/Ram-466.github.io) — personal site

---

<p align="center">
  <a href="https://github.com/Ram-466">github.com/Ram-466</a>
</p>
