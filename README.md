# FindingTheBreakpoint
How much information can an image lose before its underlying pattern becomes unrecognizable by a machine learning model

# 🔍 Pattern Recognition Under Information Loss

## 📌 Project Overview

This project investigates how image classification models behave when input data is progressively degraded. Instead of focusing only on maximizing accuracy, this research aims to identify the **failure point (pattern collapse)** where models can no longer reliably recognize patterns.

---

## 🎯 Objective

* Analyze model performance under controlled information loss
* Identify the **collapse point** where accuracy drops significantly
* Compare different degradation methods (random vs structured)
* Evaluate **model reliability**, not just prediction accuracy

---

## 🧠 Key Concept

> AI should not only predict — it should know when it cannot be trusted.

---

## ⚙️ Methodology

### 1. Dataset

* MNIST (handwritten digits)
* Train/Test split

### 2. Model

* Convolutional Neural Network (CNN)

### 3. Degradation Techniques

* 🔹 Random Pixel Drop
* 🔹 Structured Masking (block removal)
* 🔹 Noise Injection (optional)

### 4. Evaluation

* Accuracy vs Information Loss
* Collapse Point Detection
* Comparative Analysis

---

## 📊 Experiment Pipeline

```
Load Data → Train Model → Test Accuracy → Apply Degradation → Evaluate → Plot Results
```

---

## 📉 Expected Results

* Gradual accuracy drop under random degradation
* Sharp accuracy collapse under structured masking
* Near-random accuracy (~10%) at 100% data loss

---

## 🔬 Key Findings

* Models rely heavily on structural patterns
* Not all data loss affects performance equally
* Structured degradation leads to faster failure

---

## 🚀 Real-World Applications

* 🏥 Medical Imaging (detect unreliable scans)
* 🚗 Autonomous Driving (low visibility detection)
* 📡 Astronomy (noisy/incomplete image analysis)
* 🔐 Security Systems (partial face recognition reliability)

---

## 🛠️ Technologies Used

* Python
* PyTorch
* NumPy
* Matplotlib

---

## 📂 Project Structure

```
├── data/
├── notebook.ipynb
├── model/
├── results/
├── README.md
```

---

## 📌 Future Work

* Add multiple models (SVM, advanced CNNs)
* Introduce confidence & entropy-based reliability
* Extend to real-world datasets
* Apply to medical or astronomical images

---

## 🧠 Author Insight

This project focuses on **AI reliability and failure analysis**, aiming to build systems that are aware of their own limitations.

---

## 📢 Conclusion

This work demonstrates that high accuracy alone is not sufficient. Understanding **when a model fails** is equally important for building safe and trustworthy AI systems.

---

## ⭐ Contribution

If you find this project useful, feel free to ⭐ star the repository!

---
