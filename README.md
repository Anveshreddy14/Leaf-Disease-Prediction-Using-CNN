
🌿 Leaf Disease Detection Using CNN
📌 Project Overview

This project presents a Convolutional Neural Network (CNN)-based deep learning model for plant leaf disease prediction.
With an accuracy of 89%, the model helps in identifying various plant diseases from leaf images, enabling better crop health monitoring and early intervention.

The system is further integrated into an interactive web application, allowing users to upload leaf images, receive predictions, and get recommended pesticide solutions.

🚀 Features

✅ CNN-based Model (PyTorch) – Achieved 89% accuracy on validation data.

✅ Image Preprocessing & Augmentation – Used Gamma Correction & data augmentation to improve generalization.

✅ Interactive Web App – Upload a leaf image & get disease detection + pesticide recommendation.

✅ Practical Agriculture Aid – Designed to help farmers and researchers assess plant health efficiently.

🧠 Technologies Used

Python 3.11+

PyTorch – Deep learning framework

Torchvision – Image transformations & dataset handling

Flask / FastAPI (Web Framework)

HTML, CSS, JavaScript – Frontend for the web app

OpenCV & PIL – Image preprocessing

📊 Dataset

The dataset consists of plant leaf images belonging to multiple categories (healthy & diseased).
Link for the dataset:
https://data.mendeley.com/datasets/tywbtsjrjv/1
📂 Folder structure (example):

Dataset/
│── Train/

│   ├── Healthy/

│   ├── Diseased/

│── Validation/

│   ├── Healthy/

│   ├── Diseased/
