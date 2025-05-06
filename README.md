
# 🐶🐱 Cat vs Dog Image Classifier

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images into two categories: **Cats** and **Dogs**. The model is trained on image data using the `ImageDataGenerator` for data augmentation and normalization.

---

## 🧠 Model Architecture

The model is built using the `Sequential()` API and contains:

* Convolutional layers with ReLU activation
* MaxPooling layers for downsampling
* Dropout layers to reduce overfitting
* Dense layers with a sigmoid activation for binary classification

**Input shape**: 150x150x3
**Output**: 1 (sigmoid → class 0: Cat, class 1: Dog)

---

## 🏋️‍♀️ Training Details

* **Loss Function**: Binary Crossentropy
* **Optimizer**: Adam
* **Epochs**: 10 (can be adjusted)
* **Batch Size**: 32
* **Validation Split**: Done using `validation_split` in `ImageDataGenerator`

---

## 📊 Evaluation

The model’s performance is visualized using:

* Accuracy and loss plots over epochs
* Evaluation on validation data using matplotlib

---

## ▶️ How to Run

1. Prepare your dataset with two folders: `cats` and `dogs` under the training directory.
2. Run the notebook or script.
3. The model will train and display performance plots after training.

---

## 🔮 Future Improvements

* Incorporate more convolutional layers or batch normalization
* Apply transfer learning with pre-trained models like VGG16 or ResNet
* Deploy the model using Flask, Django, or Streamlit

---

## 📌 Dependencies

```bash
tensorflow
matplotlib
numpy
```

---

