# MultiModalFusion

**MultiModalFusion** is a browser-first multimodal machine learning lab for experimenting with text, image, and tabular workflows in one lightweight interface.

It upgrades the original debug-style AI interface into a richer **research training observatory** with TensorFlow.js-powered toy modelling, live training metrics, CSV learning tools, uncertainty estimation, explainability, anomaly scanning, and model save/load workflows.

> This is an experimental in-browser ML playground. It is designed for learning, prototyping, diagnostics, and visual experimentation — not as a production large language model or production ML platform.

---

## ✨ Features

### Multimodal Toy Language Model

- Browser-based toy language model workflow
- Prompt-based pre-training and fine-tuning
- Token generation with temperature control
- Optional image input
- MobileNet-style image embedding concept
- Mixture-of-Experts inspired toy generation flow
- Vocabulary and top-prediction inspection
- Language loss tracking
- Save, load, download, rebuild, and inspect model controls

### CSV / Tabular Machine Learning

- Upload custom CSV datasets
- Load built-in sample datasets
- Classification and regression modes
- Dynamic label column selection
- Multiple architecture options:
  - Residual MLP
  - Compact fast MLP
  - Wide dropout MLP
  - Gated GLU-style MLP
- Configurable hidden units, dropout, epochs, batch size, learning rate, validation split, and test split
- Early stopping with best validation restoration
- Learning-rate schedule options:
  - Constant
  - Cosine decay
  - One-cycle warmup
  - Reduce on plateau
- Train, predict, inspect, save, load, and download tabular models
- Export predictions as CSV
- Export training history
- Automatic training report generation

### Live Training Observatory

MultiModalFusion includes a live visual dashboard for understanding model behaviour while training:

- Loss and validation loss
- Accuracy / MAE style metric tracking
- Generalization gap
- Learning-rate schedule
- Epoch speed
- Tensor memory usage
- Holdout probe
- Weight drift proxy
- Best validation loss
- Current learning rate
- Rows per second

### Model Insight Lab

- Permutation feature importance
- Model-agnostic feature explainability
- Encoded feature impact analysis
- Dataset profiling
- CSV preview
- Quality warnings
- Uncertainty and calibration panel
- Prediction set / conformal alpha controls
- Anomaly scanning tools

### Diagnostics + Debugging

- Debug log panel
- Copy logs
- Download logs
- Clear logs
- TensorFlow.js backend status
- Tensor memory tracking
- Model notes
- Theme toggle
- Backend switching
- Memory refresh
- Lab state reset

---

## 🧠 What This Project Is For

MultiModalFusion is useful for:

- Learning how in-browser machine learning workflows can be structured
- Experimenting with small toy text models
- Testing CSV classification and regression ideas
- Visualising training behaviour in real time
- Exploring uncertainty, feature importance, and diagnostics
- Building a foundation for more advanced multimodal ML interfaces
- Prototyping private, local-first ML experiments in the browser

---

## 🚀 Quick Start

### Option 1: Open Directly

Clone the repository:

```bash
git clone https://github.com/kai9987kai/MultiModalFusion.git
cd MultiModalFusion
