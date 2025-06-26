#  Multilabel Classification of Chest X-rays using CNN

This project applies deep learning for **multilabel classification** of chest X-ray images, enabling the automatic detection of multiple thoracic diseases from a single scan. Leveraging a Convolutional Neural Network (CNN), the model identifies co-occurring conditions — an important step toward faster, more reliable clinical diagnostics.

---

##  Problem Statement

Unlike single-label classification tasks, medical imaging often involves multiple conditions appearing simultaneously. This project tackles the **multilabel classification** challenge using a CNN that outputs multiple binary predictions per image, allowing it to detect diseases like:

- Atelectasis  
- Cardiomegaly  
- Effusion  
- Infiltration  
- Pneumonia  
- Pneumothorax  
... and more.

---

## 🛠 Tech Stack

- **Languages**: Python  
- **Frameworks**: TensorFlow / Keras  
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
- **Dataset**: [NIH Chest X-ray14 Dataset](https://www.kaggle.com/datasets/nih-chest-xrays/data) or similar  

---

## Key Features

- ✔️ Image preprocessing: resizing, normalization, augmentation  
- ✔️ Multilabel encoding with sigmoid activation  
- ✔️ CNN-based architecture built from scratch  
- ✔️ Evaluation metrics specific to multilabel problems  
- ✔️ Visualizations of predictions and errors  

---

##  Evaluation Metrics

- **Loss**: Binary Crossentropy  
- **Metrics**:  
  - Precision  
  - Recall  

---


