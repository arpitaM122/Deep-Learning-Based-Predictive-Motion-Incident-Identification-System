# 🧍‍♂️ Vision-Based Fall Detection System using MediaPipe & Part Affinity Fields

## 📌 Project Overview

Building a high-performance fall detection system is challenging due to the complexity of human motion and dynamic indoor environments. This project presents a **vision-based fall detection framework** that integrates **MediaPipe pose estimation** and **Part Affinity Fields (PAF)** to extract structural and spatial relationships of human body joints.

Using the **GMDCSA-24 dataset**, the extracted features are used to train multiple machine learning and deep learning classifiers, including **Support Vector Machine (SVM)**, **XGBoost**, **Artificial Neural Network (ANN)**, and **Long Short-Term Memory (LSTM)**.

By combining skeletal pose information with spatial limb orientation features, the proposed framework significantly improves detection accuracy and reduces false positives compared to traditional single-feature systems.

This system is robust, reliable, and suitable for **remote elderly care**, **indoor activity monitoring**, and **healthcare surveillance applications**.

---

## ✨ Key Features

* 🎯 Vision-based fall detection using pose estimation
* 🦴 Structural feature extraction with MediaPipe
* 🧭 Spatial relationship modeling using Part Affinity Fields (PAF)
* 🤖 Multiple classifiers: SVM, XGBoost, ANN, LSTM
* 📊 Improved accuracy with reduced false alarms
* 🏥 Designed for elderly care and indoor monitoring

---

## 🧠 Methodology

1. **Data Collection**

   * Dataset: GMDCSA-24
   * Video-based indoor activity recordings

2. **Pose Estimation (MediaPipe)**

   * Extract human skeletal keypoints from video frames
   * Track joint positions and body posture

3. **Feature Extraction (PAF)**

   * Model spatial relationships and limb orientations
   * Capture inter-joint connectivity and movement patterns

4. **Feature Fusion**

   * Combine skeletal and spatial features into a unified representation

5. **Model Training**

   * Train classifiers:

     * SVM
     * XGBoost
     * ANN
     * LSTM

6. **Prediction & Evaluation**

   * Detect fall vs non-fall activities
   * Evaluate performance using accuracy and false positive rate

---

## 🔄 Workflow

```
Video Input
     ↓
MediaPipe Pose Estimation
     ↓
PAF Feature Extraction
     ↓
Feature Fusion
     ↓
ML/DL Classifiers (SVM, XGBoost, ANN, LSTM)
     ↓
Fall / Non-Fall Prediction
```

---

## 📊 Advantages

* More robust than single-feature fall detection systems
* Handles complex human movements effectively
* Reduces false positives significantly
* Works across various indoor activities
* Scalable for real-world deployment

---

## 🏥 Applications

* Remote elderly care monitoring
* Smart home healthcare systems
* Indoor surveillance
* Assisted living environments
* Hospital patient monitoring

---

## 🛠 Technologies Used

* Python
* MediaPipe
* OpenCV
* NumPy
* Scikit-learn
* XGBoost
* TensorFlow / PyTorch (for ANN & LSTM)

---

## 📁 Dataset

* **GMDCSA-24 Dataset**
  A publicly available dataset containing indoor activity and fall scenarios for vision-based human activity recognition.

---

## 🏁 Conclusion

This project demonstrates that integrating **MediaPipe pose estimation** with **Part Affinity Fields (PAF)** creates an effective and reliable fall detection system. By leveraging both skeletal tracking and spatial relationship analysis, the framework achieves high accuracy across diverse indoor activities, making it an ideal solution for real-time elderly care and indoor monitoring systems.

---

## 📌 Future Work

* Real-time deployment on edge devices
* Integration with IoT alert systems
* Expansion to outdoor environments
* Explainable AI for medical decision support
