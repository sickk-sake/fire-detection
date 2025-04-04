#Forest Fire Detection using Deep Learning
This project uses Convolutional Neural Networks (CNNs) to detect forest fires from image data. The goal is to build a binary classifier that distinguishes between fire and non-fire images using deep learning techniques.

#Dataset
We use The Wildfire Dataset from KaggleHub. It consists of labeled images split into training, validation, and test folders.
If you're using Kaggle notebooks, the dataset is auto-downloaded using:
import kagglehub
path = kagglehub.dataset_download("elmadafri/the-wildfire-dataset")

#Features
CNN-based image classification
Real-time image visualization
GPU-enabled training (if available)
Clear dataset structure and preprocessing
Works out-of-the-box on Kaggle

#Technologies Used
Python
TensorFlow / Keras
Matplotlib
KaggleHub (for dataset access)

#How to Run
📌 On Kaggle (Recommended)
Open a Kaggle notebook.
Upload or copy this notebook.
Run all cells. GPU is enabled by default on Kaggle.

#Locally
# Clone the repo
git clone https://github.com/sickk-sake/fire-detection.git
cd fire-detection
# Install dependencies
pip install tensorflow matplotlib kagglehub
# Run the notebook
jupyter notebook Fire_Detection.ipynb
Make sure you have access to the dataset and place it in the proper directory if running locally.


#Results (coming soon...)
We'll include:
Model accuracy
Loss curves
Confusion matrix


#Author
Your Name - @sickk-sake

#License
This project is open-source and available under the MIT License.

