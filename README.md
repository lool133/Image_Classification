# Image Classification using Deep Learning

## 📌 Project Overview

This project focuses on image classification using Deep Learning techniques with TensorFlow and Keras. Multiple convolutional neural network architectures were implemented and evaluated, including a custom CNN and several Transfer Learning models. The project covers data preprocessing, image augmentation, model training, fine-tuning, and performance evaluation.

---

## 🎯 Objectives

- Build an image classification model using Deep Learning.
- Preprocess and augment image datasets.
- Implement a custom CNN model.
- Apply Transfer Learning using pre-trained models.
- Compare different model architectures.
- Evaluate classification performance.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

The dataset consists of images organized into training and testing directories.

### Dataset Preparation

- Removed unnecessary folders (e.g., `.ipynb_checkpoints`, `Class_Nothing`, `Class_Space`).
- Verified that both training and testing datasets contain the same image classes.
- Images were resized to **224 × 224** pixels.

---

## ⚙️ Data Preprocessing

- Image Resizing (224×224)
- Image Normalization
- Data Augmentation
  - Rotation
  - Zoom
  - Width Shift
  - Height Shift
  - Brightness Adjustment
  - Horizontal Flip
- Training / Validation Split

---

## 🧠 Models Used

### 1. Custom CNN
A Convolutional Neural Network built from scratch using:
- Convolutional Layers
- MaxPooling Layers
- Dropout Layers
- Dense Layers
- Softmax Output Layer

### 2. VGG16 (Transfer Learning)
- Pre-trained on ImageNet
- Frozen base layers
- Custom classification head
- Fine-tuning applied

### 3. ResNet50
- Pre-trained ResNet50 architecture
- Transfer Learning for feature extraction
- Performance comparison with other models

### 4. EfficientNet
- EfficientNet pre-trained model
- Lightweight architecture with high classification performance
- Used for comparison and experimentation

---

## 📈 Model Evaluation

The models were evaluated using:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Training Loss
- Validation Loss

---

## 📊 Visualizations

The notebook includes:

- Sample Image Visualization
- Augmented Images Preview
- Training Accuracy Curves
- Validation Accuracy Curves
- Loss Curves
- Performance Comparison

---

## 🚀 Project Workflow

1. Import required libraries.
2. Load and inspect the dataset.
3. Clean unnecessary folders.
4. Preprocess the images.
5. Apply data augmentation.
6. Create training and validation datasets.
7. Train the Custom CNN model.
8. Apply Transfer Learning using:
   - VGG16
   - ResNet50
   - EfficientNet
9. Compare model performance.
10. Evaluate and visualize the results.

---

## 📁 Project Structure

```
Image_Classification/
│
├── Image_Classification.ipynb
├── train/
├── test/
├── README.md
└── requirements.txt
```

---

## 📚 Learning Outcomes

- Image Preprocessing
- Data Augmentation
- Convolutional Neural Networks (CNN)
- Transfer Learning
- Fine-Tuning Pre-trained Models
- Deep Learning with TensorFlow/Keras
- Image Classification
- Model Evaluation

---

## 🚀 Future Improvements

- Hyperparameter tuning.
- Test additional architectures such as MobileNet and InceptionV3.
- Generate a Confusion Matrix and Classification Report.
- Deploy the trained model using Streamlit or Flask.

---

## 👨‍💻 Author

**walaa omar**
Deep Learning | Computer Vision | Data Science
