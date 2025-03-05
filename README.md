🌿 Plant Disease Prediction using CNN 🌱

A deep learning-based web application for detecting plant diseases using Convolutional Neural Networks (CNNs). The app is built with TensorFlow and Streamlit for easy deployment and user interaction.

🚀 Features
Upload an image of a plant leaf to detect diseases.
Uses a pre-trained CNN model for accurate classification.
Supports multiple plant species and diseases.
Simple and interactive web UI powered by Streamlit.
📂 Project Structure
bash
Copy
Edit
📦 Plant_Disease_Prediction
│-- 📜 main.py               # Streamlit application script  
│-- 📜 requirements.txt      # Required dependencies  
│-- 📜 Dockerfile            # Containerization for easy deployment  
│-- 📜 config.toml           # Streamlit configuration  
│-- 📜 credentials.toml      # Credentials configuration  
│-- 📜 class_indices.json    # Mapping of class indices to disease names  
│-- 📜 trained_model_link.txt # Download link for the pre-trained model  
🔧 Installation & Usage

bash
Copy
Edit
git clone https://github.com/OmKale000/Plant_Disease_Detection/tree/main
cd Plant_Disease_Prediction  
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt  
3️⃣ Download the trained model from Google Drive and place it in the trained_model/ directory.

4️⃣ Run the application:

bash
Copy
Edit
streamlit run main.py  
5️⃣ Upload an image and get the prediction! 🎉

🛠️ Tech Stack
TensorFlow – Deep learning framework for CNN model
Streamlit – Web app framework for UI
PIL – Image processing library
NumPy – Array manipulation
📌 Supported Plant Diseases
The model can classify 38 plant conditions, including healthy plants. It covers crops like Tomato, Apple, Potato, Corn, Grape, and more.

🐳 Docker Deployment
To run in a Docker container:

bash
Copy
Edit
docker build -t plant-disease-classifier .  
docker run -p 8501:80 plant-disease-classifier  
