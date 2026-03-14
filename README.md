# 🐶 Dogs vs Cats — Image Classification

> A deep learning image classifier that tells apart dogs from cats with high accuracy, built with a clean ML pipeline from notebook experimentation to a production-ready Python app.

![Demo Screenshot](assets/Screenshot%202026-03-14%20211455.png)

---

## 📌 Project Overview

This project implements a **binary image classifier** to distinguish between dogs and cats using Convolutional Neural Networks (CNN). The workflow covers everything from raw data exploration in a Jupyter notebook to a deployable Python application.

| Property | Details |
|---|---|
| **Task** | Binary Image Classification |
| **Classes** | 🐶 Dog / 🐱 Cat |
| **Framework** | Python + Deep Learning (CNN) |
| **Notebook** | `notebook/Dogs_vs_Cats_Image_...ipynb` |
| **App Entry** | `main.py` |
| **Package Manager** | `uv` (via `pyproject.toml`) |

---

## 🗂️ Project Structure
```
DOG-C.../
│
├── assets/                         # Project screenshots & demo images
│   ├── Screenshot 2026-...         # App or result screenshot 1
│   └── Screenshot 2026-...         # App or result screenshot 2
│
├── notebook/
│   └── Dogs_vs_Cats_Image_....ipynb  # EDA, model training & evaluation
│
├── main.py                         # Inference / app entry point
├── pyproject.toml                  # Project metadata & dependencies
├── uv.lock                         # Locked dependency versions
├── .python-version                 # Python version pin
└── README.md
```

---

## 🖼️ Results Preview

<table>
  <tr>
    <td><img src="assets/Screenshot 2026-03-14 211455.png" alt="Screenshot 1" width="400"/></td>
    <td><img src="assets/Screenshot 2026-03-14 211456.png" alt="Screenshot 2" width="400"/></td>
  </tr>
  <tr>
    <td align="center">Model Output / Prediction</td>
    <td align="center">Training Results / App UI</td>
  </tr>
</table>

---

## ⚙️ Setup & Installation

This project uses [`uv`](https://github.com/astral-sh/uv) for blazing-fast dependency management.

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/dogs-vs-cats.git
cd dogs-vs-cats
```

### 2. Install Dependencies
```bash
# Install uv if not already installed
pip install uv

# Create virtual environment & install deps
uv sync
```

### 3. Activate Environment
```bash
# Linux / macOS
source .venv/bin/activate

# Windows
.venv\Scripts\activate
```

---

## 🚀 Run the App
```bash
python main.py
```

Or open the notebook for full training walkthrough:
```bash
jupyter notebook notebook/Dogs_vs_Cats_Image_....ipynb
```

---

## 🧠 Model Pipeline
```
Raw Images
    ↓
Data Preprocessing (resize, normalize, augment)
    ↓
CNN Architecture (Conv → Pool → Flatten → Dense)
    ↓
Training & Validation
    ↓
Model Evaluation (Accuracy, Loss curves)
```

---

## 📊 Key Features

- ✅ **End-to-end pipeline** — from raw data to prediction
- ✅ **Jupyter Notebook** — detailed EDA, training, and evaluation
- ✅ **Modular codebase** — clean `main.py` for inference
- ✅ **Reproducible** — locked deps via `uv.lock` + `.python-version`
- ✅ **Lightweight setup** — managed with modern `uv` package manager

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| TensorFlow / PyTorch | Deep learning framework |
| NumPy / Pandas | Data manipulation |
| Matplotlib / Seaborn | Visualization |
| Jupyter Notebook | Experimentation |
| uv | Dependency management |

---

## 📁 Dataset

> Dataset used: [Kaggle Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data)

- 25,000 labeled images (12,500 dogs + 12,500 cats)
- Split into train / validation / test sets

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.


---

<p align="center">Made with ❤️ | Dogs vs Cats Classifier</p>