🌿 Crop Disease Detection and Severity Estimation System

📌 Overview This project presents an intelligent system for detecting crop diseases from leaf images, estimating disease severity, and providing actionable treatment recommendations. It combines deep learning, image segmentation, explainable AI, and a simple advisory chatbot to support farmers in making informed decisions.

The system is built using PyTorch-based models and deployed through a Flask web application for easy interaction.

🚀 Features

Crop disease classification using deep learning models
Disease severity estimation using image segmentation
Visualization of infected regions on leaf images
Explainable AI using Grad-CAM
Decision support system for treatment recommendations
Chatbot for user interaction and guidance
Flask-based web interface with image upload functionality
🛠 Tech Stack

Python
Flask
PyTorch
OpenCV
NumPy
Matplotlib
Scikit-learn
📂 Project Structure

crop_disease_prediction/

│

├── app.py

├── README.md

├── requirements.txt

├── .gitignore

│

├── notebooks/

│ ├── classification.ipynb

│ ├── segmentation.ipynb

│

├── utils/

├── static/

├── templates/

├── database/

│ └── signup.db

📊 Datasets Used

🔹 Classification Dataset PlantVillage Dataset
https://www.kaggle.com/datasets/karagwaanntreasure/plant-disease-detection/data

🔹 Segmentation Dataset Plant Disease Segmentation Dataset
https://www.kaggle.com/datasets/weitianqi/plantseg

⚙️ System Workflow

Import required packages
Load and explore classification and segmentation datasets
Perform image preprocessing (resize, normalization, augmentation)
Segment infected regions using U-Net
Estimate disease severity based on infected area
Classify disease using deep learning models (ResNet, EfficientNet, DenseNet)
Train models with proper data splitting and evaluation metrics
Apply Grad-CAM for explainability
Provide treatment recommendations using decision support module
Integrate chatbot for user assistance
Deploy system using Flask web application
🧠 Models Used 🔹 Segmentation

U-Net
Residual Networks (ResNet variants)
🔹 Classification

ResNet50
EfficientNet
DenseNet
📈 Evaluation Metrics

Accuracy
Precision
Recall
F1 Score
IoU (for segmentation)
▶️ How to Run the Project

Step 1: Clone the repository git clone https://github.com/YOUR_USERNAME/REPO_NAME.git

cd REPO_NAME

Step 2: Install dependencies

pip install -r requirements.txt

Step 3: Run the application

python app.py

Open in browser:

http://127.0.0.1:5000
