# 🧠 DL-Project-Group19: End-to-End Liver and Tumor Segmentation with Explainability

> Built with purpose. Backed by science. Powered by deep learning.

## 📌 Project Overview

This project implements a full end-to-end medical image segmentation pipeline to detect and localize liver tumors from CT scans. We combine **U-Net based segmentation**, **SHAP explainability**, and **LLM-based report generation** into one clinically-relevant system — a prototype for the future of AI-assisted radiology.

---

## 🚀 Pipeline Components

- **Liver Segmentation**  
  High-performance EfficientNet-based U-Net trained to segment liver regions with Dice scores consistently over **0.94**.

- **Tumor Segmentation**  
  Secondary U-Net model focused on detecting liver tumors, despite sparse and variable lesion sizes, achieving Dice ≈ **0.83**.

- **Explainability with SHAP**  
  Visual overlays highlighting which regions most influenced the model’s decisions — bringing trust to predictions.

- **Medical Report Generation**  
  Integration with the **LLaVA Vision-Language Model**, converting CT images and masks into natural language reports for clinical interpretation.

---

## 💡 Key Results

| Task               | Dice Score | F1 Score | IoU Score |
|--------------------|------------|----------|-----------|
| Liver Segmentation | 0.94       | 0.94     | 0.92      |
| Tumor Segmentation | 0.83       | 0.83     | 0.81      |

- 📈 Accuracy over **96%**
- 🔍 End-to-end interpretability
- 📄 Report outputs readable by doctors and researchers

---

## 🧪 Advanced Features

- ✅ **t-SNE Visualization** of learned representations
- ⚗️ Tested SAM (Segment Anything Model) — but optimized our own custom approach instead
- 🔬 Built for real-world deployment potential at **Shaukat Khanum** and ongoing research with **University of Maryland** & **Brown University**

---

## 👥 Contributors

- **Hassan Imran** — Liver segmentation, explainability, model architecture  
- **Ryef Taimur** — Tumor segmentation, LLM integration, evaluation pipeline

---
## 📚 References

- University of Florida Cancer Center. *Noninvasive Blood Testing for Liver Cancer* (2024)  
  https://cancer.ufl.edu/2024/01/16/research-snapshot-noninvasive-blood-testing-method-shows-promise-in-evaluating-liver-cancer/

- Ronneberger et al., *U-Net: Convolutional Networks for Biomedical Image Segmentation*, MICCAI 2015  
- Lundberg & Lee, *A Unified Approach to Interpreting Model Predictions*, NeurIPS 2017  
- Liu et al., *LLaVA: Visual Instruction Tuning*, 2023  
- LiTS Dataset: *Liver Tumor Segmentation Challenge*

---

## 🌍 Future Plans

This repository is just the beginning. With real-world deployment goals and academic research partnerships ahead, this system will continue to evolve.

---

> _"We didn’t just build a model — we built hope."_
