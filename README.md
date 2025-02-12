# Potato Disease Classification Using Deep Learning
This project implements a deep learning model to classify potato diseases from images of potato leaves. The model is based on Convolutional Neural Networks (CNN), leveraging TensorFlow and Keras to detect and predict various potato leaf diseases.

## Problem Statement
Potato farming is one of the most important agricultural practices, but it is often affected by various diseases that reduce crop yields. This project aims to assist farmers in identifying these diseases using deep learning techniques, enabling early detection and preventive measures.

## Dataset
The dataset used in this project consists of images of potato leaves affected by various diseases such as Early Blight, Late Blight, and other common potato diseases. The dataset was sourced from .

## Dataset Structure:
-**Healthy:** Images of healthy potato leaves.
***Early Blight:** Images of potato leaves affected by Early Blight disease.
+**Late Blight:** Images of potato leaves affected by Late Blight disease.

## Model Architecture
The classification model is built using Convolutional Neural Networks (CNN), which are well-suited for image classification tasks. The network architecture is optimized to provide accurate predictions on the potato disease dataset.

## Key Steps:
-Data Preprocessing: Images are resized, normalized, and augmented to improve model performance.
*Model Training: A CNN model is trained using TensorFlow/Keras, with multiple layers to extract important features from the images.
+Model Evaluation: The model's accuracy and performance are evaluated using test data, and metrics like precision, recall, and F1-score are used to assess classification quality.
Features
Image Classification of Potato Leaf Diseases using a CNN model.
Data augmentation techniques (rotation, zoom, flip) applied for model generalization.
Saved model in .h5 format for easy deployment and inference.
FastAPI-based backend for deploying the model and making predictions through a web interface (optional).
How to Use
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/Potato-Disease-Classification.git
Install the required dependencies: Make sure you have Python 3.x installed. Then, create a virtual environment and install the dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
Run the model inference: To make predictions, run the script app.py (or replace with your app's script name):

bash
Copy
Edit
python app.py
This will start the server and allow you to upload images to classify.

Deploy the model (optional): If you want to deploy the model with FastAPI, follow the steps provided in the deploy/ folder to set up the server.

Project Structure
data/: Contains the dataset files.
models/: Contains the saved model files.
notebooks/: Jupyter notebooks for exploratory data analysis (EDA) and model evaluation.
src/: Source code files for training the model and preprocessing the data.
app.py: Main script to run model inference and serve predictions.
requirements.txt: Python dependencies for the project.
README.md: Project documentation and instructions.
Model Evaluation
The model was evaluated on accuracy, precision, recall, and F1-score. Results show that the model achieves an accuracy of over 90% on the test set, making it suitable for deployment in real-world applications.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests for any improvements.
