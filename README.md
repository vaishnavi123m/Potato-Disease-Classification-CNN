# Potato Disease Classification Using CNN

This project aims to classify potato leaf diseases using Convolutional Neural Networks (CNN). By leveraging a large dataset of potato leaf images, this model identifies early blight and late blight with high accuracy. The project includes model building, optimization, and deployment for both web and mobile platforms.

---

## 🚀 Features
- **Disease Classification**: Detects early and late blight in potato leaves.
- **High Accuracy**: Achieved 98% accuracy on a dataset of over 10,000 images.
- **Web & Mobile Accessibility**: Deployed on a ReactJS web app and React Native mobile app.
- **Optimized Model**: TensorFlow Lite and quantization techniques for fast and efficient predictions.

---

## 🛠️ Tech Stack
### **Model Building**
- **Framework**: TensorFlow
- **Architecture**: Convolutional Neural Networks (CNN)
- **Techniques**: 
  - Data Augmentation
  - TensorFlow Dataset API

### **Backend Server and MLOps**
- **Tools**: TensorFlow Serving, FastAPI

### **Model Optimization**
- **Techniques**: Quantization, TensorFlow Lite

### **Frontend Development**
- **Technologies**: ReactJS (web), React Native (mobile)

### **Deployment**
- **Platform**: Google Cloud Platform (GCP)
- **Services**: Google Cloud Functions (GCF)

---

## 📂 Project Structure
```plaintext
.
├── data/                 # Dataset for training and testing
├── model/                # Trained models and scripts
├── backend/              # FastAPI backend server
├── frontend/             # ReactJS frontend code
├── mobile/               # React Native mobile app
├── README.md             # Project documentation
└── requirements.txt      # Python dependencies
