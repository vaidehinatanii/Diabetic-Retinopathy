# Diabetic-Retinopathy
🧠 Diabetic Retinopathy Detection Using EfficientNet
📌 Overview

This project presents a deep learning–based approach for automated Diabetic Retinopathy (DR) detection using transfer learning with the EfficientNet-B0 architecture. The model classifies retinal fundus images into two categories: No Diabetic Retinopathy and Presence of Diabetic Retinopathy.
The goal is to build a computationally efficient and accurate system that can assist early screening and support healthcare professionals.

🎯 Objectives

Develop an automated DR detection system using deep learning.
Apply transfer learning with EfficientNet-B0 for feature extraction.
Perform binary classification of retinal fundus images.
Build a lightweight and efficient architecture suitable for real-world deployment.
Evaluate performance using standard classification metrics.

🗂 Dataset

APTOS 2019 Blindness Detection Dataset
High-resolution retinal fundus images.
Images resized to 224×224 for EfficientNet input.
Binary classification:
No DR
DR Present

⚙️ Methodology
🔹 Preprocessing

Image resizing and normalization
Data augmentation:
Rotation
Horizontal flipping
Zoom

🔹 Model Architecture

EfficientNet-B0 (pretrained on ImageNet)
Global Average Pooling Layer
Dropout Layer
Dense Sigmoid Output Layer

🔹 Training Strategy

Freeze base layers initially
Fine-tune upper layers with lower learning rate
Optimizer: Adam
Loss Function: Binary Cross-Entropy

📊 Results
Metric	Value
Accuracy	0.94
Precision	0.928
Recall	0.931
F1 Score	0.94
ROC-AUC	0.985
The model demonstrates strong performance with balanced precision and recall, indicating reliable DR detection.

🧪 Evaluation Metrics

Accuracy
Precision
Recall
F1-score
Confusion Matrix
ROC Curve & AUC

🛠️ Tech Stack

Python
TensorFlow / Keras
NumPy
scikit-learn
Matplotlib
Google Colab (GPU)

🚀 How to Run

1️⃣ Clone Repository
git clone https://github.com/yourusername/repository-name.git
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run Notebook
Open the .ipynb file in Google Colab or Jupyter Notebook and execute cells sequentially.

📌 Project Structure
├── dr_detection_efficientnet.ipynb
├── README.md
├── images/
├── results/
└── requirements.txt

🔮 Future Work

Multi-class DR severity classification.
Deployment as a real-time web or mobile application.
Testing on larger multi-center retinal datasets.

👩‍💻 Authors

Vaidehi Natani
Yuvraj Singh
Department of Computer Science and Engineering
Manipal University Jaipur
