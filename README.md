# 🛰️ Satellite Image Segmentation Project

## 📌 Project Overview
This project focuses on semantic segmentation of satellite imagery using deep learning.  
The goal is to identify and segment specific land features from multi-band satellite images.

---

## 🗂 Dataset Description

- Multi-band satellite images (12 bands)
- Corresponding segmentation masks
- Images format: `.tif`
- Masks format: `.png`

---

## ⚙️ Preprocessing

- Convert images to float32
- Normalize pixel values
- Prepare masks (binary format)

---

## 🧠 Model

- U-Net architecture
- Loss: BCELoss
- Optimizer: Adam
- Evaluation Metric: IoU / Dice Score

---

## Author
**Alaa Sayed** - AI Engineer
