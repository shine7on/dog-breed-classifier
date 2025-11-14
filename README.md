Dog Breed Classifier – AI Web App

An AI-powered web application that predicts dog breeds from uploaded images using CNN + Transfer Learning (TensorFlow).

🚀 Overview

This project uses Convolutional Neural Networks (CNNs) and transfer learning to identify dog breeds from images.
The model is trained on the Stanford Dogs Dataset (120 breeds, 20,000+ images) and deployed in a Streamlit web app.

Users can upload a dog photo → the model predicts the most likely breed → the app displays breed information.


🧠 Tech Stack
AI / Model
TensorFlow + Keras
Transfer Learning (MobileNetV2 / ResNet50)
Google Colab (GPU training)
Web App
Streamlit
Python
JSON metadata for breed info


📂 Project Structure

model/
 └── model_training.ipynb      # CNN training notebook
app/
 ├── app.py                    # Streamlit app
 ├── breeds.json               # Dog breed info
 └── requirements.txt          # Dependencies
assets/
 ├── sample_images/
 └── screenshots/


🐕 Dataset

Stanford Dogs Dataset
120 dog breeds · ~20,000 images
Download: https://www.kaggle.com/jessicali9530/stanford-dogs-dataset


📊 Features

Upload an image to classify breed
Top-3 predictions + confidence scores
Breed info (size, temperament, lifespan)
Mobile-friendly UI
Deployed on the web


🎥 Demo (coming soon)

Link to demo video or GIF.