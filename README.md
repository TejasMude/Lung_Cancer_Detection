# Lung_Cancer_Detection
🫁 Lung Cancer Detection using CNN
This project implements a deep learning model using Convolutional Neural Networks (CNNs) to detect lung cancer from chest CT scan images. A user-friendly interface is built using Streamlit for real-time image prediction.

🔍 Features
Detects potential lung cancer from CT scan images using a trained CNN model.
Easy-to-use web interface powered by Streamlit.
Displays prediction results with confidence.
Upload and test your own CT scan images.
Visual representation of input image and classification result.

🧠 Model Summary
Algorithm: Convolutional Neural Network (CNN)
Training Dataset: Chest CT scan images (e.g., LIDC-IDRI)
Input: 2D CT Scan Images
Output: Cancer / No Cancer prediction
Framework: TensorFlow / Keras

💾 Dataset Used
Dataset Name: Chest CT Scan Dataset
Source: Publicly available lung CT scan datasets like LIDC-IDRI
Format: Images (.jpg/.png/.dcm converted)
Classes: Positive (Cancerous) Negative (Non-cancerous)

⚙️ Technical Stack
Component	  Technology
Frontend:	  Streamlit
Backend:	  Python
Model	CNN:  (TensorFlow/Keras)
Dataset:	  Chest CT Images
Libraries:	OpenCV, NumPy, Pandas, PIL, TensorFlow, Streamlit

✅ Prerequisites
Install the required libraries before running the project:
pip install streamlit tensorflow opencv-python pillow numpy pandas

🚀 How to Run the Project
1. Clone the repository (if hosted):
git clone https://github.com/yourusername/lung-cancer-detection.git 
cd lung-cancer-detection

2. Add the model file:
Ensure the trained CNN model is saved as model.h5 in the project folder.

3. Run the Streamlit app:
streamlit run app.py

4. Upload a CT scan image in the browser interface and get prediction instantly.

⭐ Link for download the Chest CT Scan Images dataset:
https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
