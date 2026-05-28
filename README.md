# 🦠 Malaria Detection using Convolutional Neural Networks (CNN)

## 📌 Overview
This project focuses on detecting malaria-infected red blood cells using a Convolutional Neural Network (CNN). The model classifies microscopic cell images as **Parasitized** or **Uninfected** using deep learning techniques, helping automate the malaria diagnosis process and reduce dependency on manual microscopy.

---

## 🚀 Features
- CNN-based image classification
- Detection of malaria-infected blood cells
- Image preprocessing and augmentation
- Batch normalization and dropout for improved model performance
- High accuracy with reduced overfitting
- Training and validation performance visualization

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries & Frameworks:**  
  - TensorFlow / Keras  
  - NumPy  
  - Pandas  
  - Matplotlib  
  - OpenCV  
  - Scikit-learn  

---

## 📂 Dataset
The project uses the **NIH Malaria Cell Images Dataset**, which contains thousands of labeled microscopic images of:
- Parasitized Cells
- Uninfected Cells

🔗 Dataset Link:  
https://ceb.nlm.nih.gov/repositories/malaria-datasets/

---

# ⚙️ Project Workflow

## 1️⃣ Data Preprocessing
- Resized images to uniform dimensions
- Normalized pixel values
- Applied image augmentation techniques:
  - Rotation
  - Flipping
  - Zooming
  - Shearing

---

## 2️⃣ CNN Model Architecture
The model includes:
- Convolutional Layers
- Max Pooling Layers
- Batch Normalization
- Dropout Layers
- Dense Layers
- Sigmoid Activation Function

---

## 3️⃣ Model Training
- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy
- **Evaluation Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1-Score

---

## 📊 Results
- Achieved high classification accuracy on test data
- Successfully classified infected and healthy cell images
- Reduced overfitting using dropout and augmentation techniques

---

# 📁 Folder Structure

```bash
Malaria-Detection-CNN/
│── dataset/
│── models/
│── notebooks/
│── images/
│── train.py
│── app.py
│── requirements.txt
│── README.md
```

---

# 💻 Installation & Setup

## Clone the Repository
```bash
git clone https://github.com/your-username/malaria-detection-cnn.git
```

## Navigate to the Project Directory
```bash
cd malaria-detection-cnn
```

## Install Dependencies
```bash
pip install -r requirements.txt
```

## Run the Project
```bash

```

---

# 🔮 Future Improvements
- Deploy as a web application
- Real-time malaria detection using webcam input
- Improve accuracy using transfer learning models
- Add support for multiclass disease detection

---

# 🌍 Applications
- Healthcare diagnostics
- Medical image analysis
- AI-assisted disease detection
- Rural healthcare support systems

---

# 👩‍💻 Author
**Anisa Arora**  

🔗 GitHub: https://github.com/Anisa2606
