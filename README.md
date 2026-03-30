🌱 Plant Disease Detection System
📌 Project Description

The Plant Disease Detection System is an AI-powered application that helps farmers and gardeners identify plant diseases early by analyzing leaf images. Using computer vision and deep learning, the system classifies whether a plant is healthy or diseased, and identifies the type of disease when present. It can provide recommendations for treatment or prevention, helping reduce crop loss and improve yields.

🛠️ Tech Stack / Requirements

Programming Language: Python 3.x

Libraries:

tensorflow or pytorch – for deep learning

opencv-python – image processing

numpy – numerical operations

pandas – data handling

matplotlib / seaborn – visualization

flask or streamlit – optional web interface

Hardware: GPU recommended for faster training (optional if using pre-trained models)

Dataset: Pre-labeled images of plant leaves for training the model

⚙️ How to Run

Clone the repository

git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection


Create a virtual environment

python -m venv venv
# Activate it
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate


Install dependencies

pip install -r requirements.txt


Run the application

If using a script:

python main.py


If using Streamlit:

streamlit run app.py


Use the system:

Upload a leaf image.

The model predicts healthy or diseased.

If diseased, the system outputs the type of disease and possible recommendations.

✅ Optional: Include sample images in the data/ folder for testing the system.
