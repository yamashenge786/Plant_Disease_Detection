🌱 Plant Disease Detection System
📌 Project Overview

The Plant Disease Detection System is an AI-powered application designed to help farmers and gardeners detect plant diseases early by analyzing leaf images.

Using Computer Vision and Deep Learning, the system classifies whether a plant leaf is healthy or diseased, and identifies the specific disease type when present.

By providing early detection and treatment recommendations, the system helps:

🌾 Reduce crop loss
📈 Improve agricultural productivity
💰 Minimize financial losses
🌍 Support sustainable farming practices
🚀 Live Demo


🛠️ Tech Stack
💻 Programming Language
Python 3.x

📚 Libraries & Frameworks
TensorFlow / PyTorch – Deep learning model development
OpenCV – Image preprocessing
NumPy – Numerical computations
Pandas – Data handling
Matplotlib / Seaborn – Data visualization
Flask / Streamlit – Web application interface

🖥️ Hardware
GPU recommended for faster model training (optional when using pre-trained models)

📂 Dataset
Pre-labeled plant leaf images for supervised learning
Dataset should contain both healthy and diseased leaf samples

🧠 How It Works
User uploads a leaf image.
Image is preprocessed (resizing, normalization, etc.).
The trained deep learning model performs classification.
Output is displayed:
Healthy 🌿
Diseased 🍂 (with disease name + recommendations)
