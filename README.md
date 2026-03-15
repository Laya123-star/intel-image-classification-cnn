# 🌄 Intel Image Classification using CNN (Deep Learning)

A deep learning project focused on building and evaluating a **Convolutional Neural Network (CNN)** for **multi-class image classification** using the **Intel Image Classification dataset**.

---

# 📘 Project Overview

This project implements a **Convolutional Neural Network (CNN)** to classify natural scene images into multiple categories.

The project covers the complete deep learning pipeline including:

- Dataset exploration
- Image preprocessing
- Data augmentation
- CNN architecture design
- Model training and validation
- Model evaluation using performance metrics
- Prediction visualization

The goal is to build a **robust CNN model capable of accurately classifying real-world natural scenes**.

---

# 🎯 Objective

The main objectives of this project are:

🔹 Understand the structure of an image dataset  
🔹 Perform image preprocessing and augmentation  
🔹 Build a CNN architecture from scratch  
🔹 Train the model using TensorFlow/Keras  
🔹 Evaluate model performance using multiple metrics  
🔹 Visualize model predictions on unseen test images  

---

# 📂 Dataset Information

The dataset used is the **Intel Image Classification Dataset** available on Kaggle.

Dataset Link:  
https://www.kaggle.com/datasets/puneet6060/intel-image-classification

### Dataset Details

| Feature | Description |
|------|-------------|
| Total Images | 25,000+ |
| Image Type | Natural Scene Images |
| Number of Classes | 6 |
| Image Size | Resized to 150 × 150 |

### Target Classes

The dataset contains **6 scene categories**:

- 🏢 Buildings  
- 🌲 Forest  
- 🧊 Glacier  
- ⛰ Mountain  
- 🌊 Sea  
- 🛣 Street  

Each image belongs to **one of the above categories**.

---

# 🧹 Data Preprocessing

Before training the CNN model, several preprocessing steps were applied:

### ✔ Image Resizing
All images were resized to **150 × 150 pixels** to maintain uniform input size.

### ✔ Pixel Normalization
Pixel values were scaled to the range **0–1** by dividing by 255.

### ✔ Train / Validation / Test Split
The dataset was split into:

- **Training Set**
- **Validation Set**
- **Test Set**

This ensures the model is evaluated on **unseen data**.

### ✔ Data Augmentation

To improve model generalization and prevent overfitting, the following augmentation techniques were used:

- Image Rotation
- Horizontal Flip
- Zoom
- Width & Height Shift
- Shear Transform

Data augmentation increases dataset diversity without collecting new data.

---

# 🧠 CNN Model Architecture

A **Convolutional Neural Network (CNN)** was built from scratch using **TensorFlow / Keras**.

### Architecture Components

The CNN model includes:

✔ Convolutional Layers (Feature Extraction)  
✔ ReLU Activation Function  
✔ Max Pooling Layers  
✔ Dropout Layers for Regularization  
✔ Fully Connected (Dense) Layers  
✔ Softmax Output Layer for Multi-Class Classification  

### Model Flow

Input Image  
⬇  
Convolution Layer  
⬇  
ReLU Activation  
⬇  
Max Pooling  
⬇  
Convolution Layer  
⬇  
Pooling  
⬇  
Fully Connected Layers  
⬇  
Softmax Output Layer  

---

# ⚙ Model Training

The CNN model was trained using the **training dataset** and validated using the **validation dataset**.

### Training Techniques Used

- **Early Stopping** to prevent overfitting
- **Model Checkpointing** to save the best model
- **Batch Training**
- **Validation Monitoring**

### Training Visualization

Training progress was monitored using:

- **Training Accuracy vs Validation Accuracy**
- **Training Loss vs Validation Loss**

These graphs help identify **overfitting or underfitting**.

---

# 📊 Model Evaluation

After training, the model was evaluated using the **test dataset**.

### Evaluation Metrics

The following metrics were used to measure model performance:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

These metrics provide detailed insight into classification performance for each class.

---

# 🔍 Prediction Visualization

To better understand the model’s performance:

- **10 random test images** were selected
- Each image was displayed with:
  - **Actual Label**
  - **Predicted Label**

This helps visually verify the correctness of model predictions.

---

# 🛠 Tech Stack

| Tool | Purpose |
|----|----|
| Python | Programming language |
| TensorFlow / Keras | Deep learning framework |
| NumPy | Numerical computation |
| Matplotlib | Visualization |
| Seaborn | Confusion matrix visualization |
| OpenCV / PIL | Image processing |
| Google Colab / Jupyter Notebook | Development environment |

---

# 📁 Repository Structure

Intel-Image-Classification-CNN/

```
├── CNN_Image_Classification.ipynb
├── README.md
```

---

# 🚀 How to Run the Project

1️⃣ Open the notebook in **Google Colab or Jupyter Notebook**

2️⃣ Install required libraries if needed:

```python
pip install tensorflow matplotlib numpy seaborn
```

3️⃣ Download the dataset from Kaggle.

4️⃣ Update the dataset path in the notebook.

5️⃣ Run all cells sequentially to:

- Preprocess images
- Train the CNN model
- Evaluate the model
- Visualize predictions

---

# 🧠 Key Learning Outcomes

✔ Understanding CNN architecture  
✔ Image preprocessing techniques  
✔ Data augmentation for deep learning  
✔ Training and tuning deep learning models  
✔ Evaluating classification performance  
✔ Visualizing model predictions  

---

# 📌 Academic Submission

This repository was created as part of a **Deep Learning assignment** to demonstrate the design, training, and evaluation of a **Convolutional Neural Network (CNN)** for real-world image classification.
