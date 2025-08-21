# 🧪 NeurIPS – Open Polymer Prediction

This repository contains my solutions, experiments, and models for the **NeurIPS Open Polymer Prediction Challenge**.  
The goal of the competition is to predict **polymer properties** (e.g., FFV, Tg, etc.) from molecular SMILES representations using machine learning methods.

---

## 📂 Repository Structure
```
NeurIPS---Open-Polymer-Prediction/
│
├── Neural_Network.ipynb              # Neural network model training
├── XGBoost_same_embeddings.ipynb     # XGBoost with same embeddings
├── XGBoost_different_embeddings.ipynb# XGBoost with different embeddings
├── data/                             # (optional) Place for datasets
└── README.md                         # Project documentation
```

---

## ⚙️ Setup & Installation

Clone the repo:
```bash
git clone https://github.com/Ankit-Chitosiya/NeurIPS---Open-Polymer-Prediction.git
cd NeurIPS---Open-Polymer-Prediction
```

---

## 🚀 Usage

Run the Jupyter notebooks to train and evaluate models:  
```bash
jupyter notebook
```

Open:
- `Neural_Network.ipynb` for neural network training  
- `XGBoost_same_embeddings.ipynb` / `XGBoost_different_embeddings.ipynb` for gradient boosting  

---

## 📊 Models & Public Results
- **Neural Network** → RMSLE: **0.110**  
- **XGBoost (same embeddings)** → RMSLE: **0.76**  
- **XGBoost (different embeddings)** → RMSLE: **0.74**  

---

## 🙌 Acknowledgements
- NeurIPS Open Polymer Prediction challenge organizers  
- RDKit for molecular feature extraction  
- Scikit-learn, XGBoost, PyTorch for ML pipelines  

