# Task 3 – CNN Image Classification with TensorFlow

## 🎯 Objective
Build a Convolutional Neural Network (CNN) for image classification using the **CIFAR-10 dataset** in TensorFlow, and evaluate model performance on a test dataset.

---

## 📂 Deliverable
A functional deep learning model with:
- Data loading and preprocessing
- CNN architecture with convolution, pooling, and dropout
- Accuracy visualization over epochs
- Model evaluation on test dataset

---

## 🖼️ Dataset
- Dataset: **CIFAR-10**
- Classes: 10 object categories
- Source: `tf.keras.datasets.cifar10`

---

## ⚙️ Tech Stack
| Component           | Tool/Library         |
|--------------------|----------------------|
| Model Framework     | TensorFlow / Keras   |
| Data Augmentation   | `ImageDataGenerator` |
| Model Layers        | Conv2D, MaxPooling2D, Dense |
| Evaluation          | Accuracy, Loss Graphs |
| Model Saving        | `model.save()`       |

---

## 🧠 CNN Model Architecture
- 3 Convolutional layers
- 2 MaxPooling layers
- 1 Dense layer + Dropout
- Output layer with 10 classes (softmax)

---

## 🚀 How to Run

1. Open:
   ```
   main_advanced.py or main_advanced.ipynb
   ```

2. Run the script. It will:
   - Load CIFAR-10 data
   - Apply data augmentation
   - Train a CNN model
   - Plot training/validation accuracy
   - Save model to `cnn_model.h5`

---

## 📈 Outputs
- `train_accuracy.png`: Training vs validation accuracy
- `cnn_model.h5`: Trained model file

---

## 📁 Files
| File               | Description                          |
|--------------------|--------------------------------------|
| `main_advanced.py` | CNN training script                  |
| `cnn_model.h5`     | Saved trained model                  |
| `train_accuracy.png` | Accuracy plot                      |

---

## 👨‍💻 Author
**Agatheeswaran R**  
Codetech ML Internship – Final Task 3
