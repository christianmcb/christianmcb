# Christian McBride

Data Scientist working on predictive modelling, forecasting, and applied research, with a focus on rigorous experimentation, honest evaluation, and turning messy data into decisions you can defend.

My background spans tabular ML, time-series forecasting, computer vision, and self-supervised learning. I care about the parts of data science that are easy to get wrong: validation design, leakage, imbalanced data, and the gap between a headline metric and what a model actually does in practice.

## Featured projects

### Pricing ML Engine
A cross-sell prediction project on imbalanced tabular data, built end-to-end from EDA through model selection to a deployable artefact.

Highlights:
- Stratified cross-validation and hyperparameter tuning across RandomForest, XGBoost, and LightGBM
- **ROC-AUC 0.858** on the held-out set, with calibration and threshold analysis to support business decisions
- Drift monitoring across 4,000 predictions to surface distribution shift post-deployment

**Tech:** Python, scikit-learn, XGBoost, LightGBM, Pandas  
**Repo:** [https://github.com/christianmcb/pricing_ml_engine](https://github.com/christianmcb/pricing_ml_engine)

---

### Demand Forecasting ML System
A retail forecasting pipeline built around the validation problems that quietly wreck most forecasting work.

Highlights:
- Strict chronological validation to avoid temporal leakage
- MLflow-tracked experiments comparing feature sets and model variants
- Feature engineering focused on lags, rolling statistics, and calendar effects

**Tech:** Python, Pandas, LightGBM, MLflow  
**Repo:** [https://github.com/christianmcb/demand_forecasting_ml](https://github.com/christianmcb/demand_forecasting_ml)

---

### Investment Research Copilot
An LLM-assisted analytical workflow for portfolio analysis, combining holdings data, company fundamentals, market data, and news into structured reports.

Highlights:
- Ingests portfolio holdings and enriches them across multiple data sources
- Produces sector-exposure and attribution analysis in a Streamlit interface
- Designed for exploratory analysis rather than black-box recommendations

**Tech:** Python, Pandas, Streamlit, financial APIs, LLM integration  
**Demo:** [https://investmentresearchcopilot-btmptvaly25gzuqxikzupk.streamlit.app](https://investmentresearchcopilot-btmptvaly25gzuqxikzupk.streamlit.app)

---

### U-Net Segmentation Evaluation
A medical image segmentation pipeline supporting the experimental work behind my ISBI 2024 publication.

Highlights:
- Multi-colour-space feature comparison with controlled experimental design
- Reproducible preprocessing and evaluation workflows
- +0.0187 IoU and +0.0183 Dice improvements across validation sets

**Tech:** Python, PyTorch, OpenCV  
**Repo:** [https://github.com/christianmcb/pytorch-unet-segmentation](https://github.com/christianmcb/pytorch-unet-segmentation)

---

### Deeploi
A lightweight framework for wrapping trained models as FastAPI services — used to close the loop between model experiments and usable predictions in my own projects.

**Tech:** Python, FastAPI, Pydantic, scikit-learn, XGBoost, Docker  
**Repo:** [https://github.com/christianmcb/deeploi](https://github.com/christianmcb/deeploi)

## Research

My research has focused on self-supervised learning, facial motion analysis, and medical image segmentation, with recurring themes around evaluation integrity and detecting hidden data leakage in published benchmarks.

Selected publications:
- **Multi-Colour Space Channel Selection for Chronic Wound Segmentation** — ISBI 2024 [Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10635155&casa_token=2YSkR4iDaOIAAAAA:jJ3msBWgx6SZ5lCR8W3Eyw4XARhsaGrn_RW3Mg2BVPpHn3alG7Mm92wGtDIrXIJV_QMZyboGyHs&tag=1)
- **Gaussian Random Fields as an Abstract Representation of Patient Metadata for Multimodal Medical Image Segmentation** — Scientific Reports, 2025 [Link](https://www.nature.com/articles/s41598-025-03393-x)
- **Enhanced Harmonic Densely Connected Hybrid Transformer Network for Chronic Wound Segmentation** — Computers in Biology and Medicine, 2025 [Link](https://www.sciencedirect.com/science/article/pii/S0010482525005232)

## Links

- **LinkedIn:** [https://www.linkedin.com/in/christianmcb8/](https://www.linkedin.com/in/christianmcb8/)
- **GitHub:** [https://github.com/christianmcb](https://github.com/christianmcb)
