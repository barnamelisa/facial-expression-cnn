# 🧠 CNN Image Classifier - Clasificare Expresii Faciale cu Rețele Neuronale Convoluționale

Acest proiect dezvoltă două modele de rețele neuronale convoluționale (CNN) pentru clasificarea imaginilor în funcție de expresii faciale. Se poate adapta ușor și la alte categorii de clasificare (ex: fructe, animale, semne rutiere etc.).

> Proiect realizat în cadrul cursului **Sisteme Inteligente** – Anul III, Semestrul II

---

## 🎯 Scopul Proiectului

Scopul este să se construiască două modele CNN care să clasifice imagini în 2–10 clase distincte. Exemplu pentru expresii faciale:

- `fericit`, `trist`, `neutru`, `surprins`, `dezgustat`, `fricos`, `furios`

---

## 🏗️ Arhitectura Modelelor

### ✅ Model Simplu
- 2 layere convoluționale (Conv2D + ReLU)
- MaxPooling
- Dense layer fully connected
- Dropout pentru regularizare
- Softmax pentru clasificare

### ✅ Model Complex
- 4–6 layere convoluționale
- Batch Normalization
- MaxPooling și Dropout
- Dense layers mai adânci
- Softmax

---

## 🧪 Experimente

- **Optimizatori:** SGD vs Adam
- **Kernel sizes:** 3x3 și 5x5
- **Tehnici de regularizare:** Dropout, BatchNormalization
- **Evaluare:** Confusion Matrix, Precision, Recall, F1-score
- **Explainability:** SHAP pentru interpretarea deciziilor

---

## 🔧 Instalare & Rulare

1. Clonează proiectul:
```bash
git clone https://github.com/nume-utilizator/proiect-cnn-expresii.git
cd proiect-cnn-expresii

