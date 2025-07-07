# Referring Image Segmentation (RIS) Research Project

## ⭐ Overall Dataset Pipeline (A2D / ViCaS)

This repository contains **action-centric captioning pipelines** for two major video segmentation datasets:  
- **A2D Dataset (Actor-Action Dataset)**  
- **ViCaS Dataset**  

The goal is to generate **action-centric captions** that enable Referring Image Segmentation (RIS) models to better understand **actions**, not just object categories.

---

## ✨ Motivation

Despite recent advances in RIS, most models are trained on datasets like **RefCOCO**, where captions are predominantly **noun-centric**, such as:

> *"The man on the left"*, *"The dog in the back"*

These descriptions lack action-level semantics. However, RIS is a task that often requires distinguishing **between multiple objects of the same category** — a situation where action-based disambiguation is critical.

To unlock **action-level comprehension**, we need captions like:

> *"The man is kicking a ball"*,  
> *"The child is climbing the stairs"*

This repository addresses that gap by proposing pipelines that generate such **verb-rich, action-centered captions** using A2D and ViCaS datasets.

---

## 💥 Why It Matters

- Improves the ability of RIS models to **distinguish same-category objects** based on actions  
- Enhances **verb understanding** in RIS models

---

## 📊 Reference Models

This project builds on:

- **[ReferFormer (CVPR 2022)](https://github.com/wjn922/ReferFormer)**  
- **[ViCaS (CVPR 2025)](https://github.com/Ali2500/ViCaS)**

---

## 📌 Key Points

✅ Designed and implemented full pipelines for both A2D and ViCaS  
✅ Applied **movability-based filtering**, action-focused instruction tuning   
✅ Significantly enriched RIS training data to enhance verb-level understanding

---

## 📬 Contact

If you have any questions, feel free to reach out!
