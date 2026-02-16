# MediScan-AI-Powered-Medical-Image-Analysis-for-Disease-Diagnosis
# Eye Disease Prediction (Retinal Image Classification)

This project classifies retinal/eye images into four categories:
- **cataract**
- **diabetic_retinopathy**
- **glaucoma**
- **normal**

The notebooks cover the full workflow: loading the dataset, preprocessing images, training a deep learning model, and testing predictions. A simple image segmentation step (thresholding) is also included to show the affected area and count segmented pixels.

> Note: This project is for learning and experimentation. It is **not** a medical tool.

---

## What this project is for
- Learn how to preprocess eye images (resize, normalize, basic enhancement).
- Train and evaluate a CNN / transfer learning model for eye disease classification.
- Try basic image segmentation to highlight regions and inspect pixel-level changes.
- Run a small demo (Tkinter UI / optional Streamlit + Flask API snippets included in the preprocessing notebook).

---

## Dataset
The code expects a folder-based dataset structure like this:

