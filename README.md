
# 🦷 Teeth Disease Classification

This project develops a convolutional neural network (CNN) using TensorFlow/Keras to classify oral and dental images into **7 distinct disease categories**. It is part of an AI-driven healthcare initiative aimed at improving dental diagnostics and patient outcomes.

---

## 📁 Project Structure

```
teeth-disease-classification/
├── data/              # Contains Teeth_Dataset with Training, Validation, Testing folders
├── model/             # Trained model file (e.g., teeth_model.h5)
├── notebooks/         # Main Jupyter Notebook used for training and evaluation
├── images/            # Saved output images (accuracy, loss, predictions)
├── README.md          # Project overview and usage instructions (this file)
```

---

## 🧠 Disease Classes

- `CaS` — Canker Sores  
- `CoS` — Cold Sores  
- `Gum` — Gum Disease  
- `MC`  — Mouth Cancer  
- `OC`  — Oral Cysts  
- `OLP` — Oral Lichen Planus  
- `OT`  — Other Lesions  

---

## 🧪 Model Overview

- Built with **TensorFlow/Keras**
- Trained from scratch on image dataset
- Uses **data augmentation** to improve generalization
- Accuracy evaluated on separate validation and test sets

---

## 📈 Accuracy and Loss over Epochs

These plots show the model's performance as training progresses.

### Accuracy over Epochs
![Accuracy Plot](images/accuracy_plot.png)

### Loss over Epochs
![Loss Plot](images/loss_plot.png)

---

## 🖼️ Sample Predictions

Example test images and the model’s predictions.

- ✅ Green = Correct  
- ❌ Red = Incorrect  

![Sample Predictions](images/predictions_sample.png)
