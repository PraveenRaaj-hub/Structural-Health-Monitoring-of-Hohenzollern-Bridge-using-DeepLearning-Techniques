# Structural Health Monitoring using Deep Learning

This project leverages **LSTM** and **U-Net** deep learning architectures to detect and locate structural defects in the **Hohenzollernbrücke** (Cologne) using **FEM-simulated** data under various loading conditions.

---

## 📊 Description

The dataset simulates different defect types and loading conditions. Two key models are developed:
- **LSTM**: Used for temporal pattern recognition and sequential classification of defect locations.
- **U-Net**: Applied for image-based or spatial localization tasks on FEM data.

---

## 📁 Files Overview

```
.
├── group-14.ipynb     # Main notebook for preprocessing and LSTM/U-Net training under various conditions
├── LSTM.ipynb         # Separate notebook for LSTM experiments focusing on defect localization
├── CIE_GROUP14_REPORT.pdf        # Final project report
├── Computational Intelligence in Engg.pdf  # Course/project context document
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Structural-Health-Monitoring-using-DeepLearning.git
cd Structural-Health-Monitoring-using-DeepLearning
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
> If no requirements.txt is present, ensure the following libraries are available:
```bash
pip install numpy pandas matplotlib tensorflow scikit-learn
```

3. Launch the main notebook:
```bash
jupyter notebook group-14.ipynb
```

---

## 🧪 Methodology

- Preprocessing FEM-simulated structural data
- Classification of defects using LSTM
- Localization using U-Net
- Evaluation of models under multiple defect types and load conditions

---

## 📄 Report

See [`CIE_GROUP14_REPORT.pdf`](./CIE_GROUP14_REPORT.pdf) for full details on experiments, results, and conclusions.

---

## 🤝 Contributors

- Group 14, CIE Project
- IAM,RWTH.

---

## 📃 License

This repository is intended for educational use only.
