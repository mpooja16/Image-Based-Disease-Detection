This project focuses on developing an automated system to detect pneumonia from chest X-ray images using deep learning techniques, specifically Convolutional Neural Networks (CNNs).

🎯 Purpose
Manual interpretation of X-rays is time-consuming and requires expert radiologists. The goal is to build a reliable AI model that can analyze X-ray images, classify them as pneumonia or normal, and assist in early diagnosis.

🧩 How It Works
Dataset:
The model is trained on ChestX-ray14, a large public dataset containing over 100,000 X-ray images with disease annotations.

Image Preprocessing:
Each X-ray is resized, normalized, and augmented to improve training and avoid overfitting.

Model Architecture:
Pre-trained CNN models like ResNet50 and DenseNet121 are used with transfer learning to improve performance even with limited data.

Training & Validation:
The dataset is split into training and testing sets. The model learns to distinguish pneumonia features based on labeled examples.

Prediction & Evaluation:
The trained model predicts whether an image shows signs of pneumonia. It is evaluated using metrics like accuracy, precision, recall, and AUC.

Visualization:
Output includes classification labels, confidence scores, and heatmaps (Grad-CAM) showing where the model focused in the image.

✅ Outcome
Achieved high accuracy and AUC, showing that deep learning can effectively detect pneumonia from chest X-rays.

Supports fast and scalable diagnosis, especially in areas lacking medical expertise.
