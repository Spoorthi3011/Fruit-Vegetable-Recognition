# 🍎🥦 Fruit & Vegetable Recognition Using AI

This project is an AI-powered image classification system for recognizing fruits and vegetables using **Convolutional Neural Networks (CNNs)** and **Transfer Learning**.

---

## 📌 Highlights

- ✅ High classification accuracy on a diverse dataset
- 🧠 Built using CNNs for pattern detection
- 🧪 Used Transfer Learning to improve performance
- 📊 Includes training/validation visualizations
- 💻 Jupyter Notebook for code and testing

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `testing_models.ipynb` | Jupyter notebook implementing the CNN model and testing it |
| `Fruit Veg reconginisation.pdf` | Full project report including dataset, architecture, results, and conclusion |

---

## 🧠 Dataset Used

- Source: [Kaggle – Fruit and Vegetable Image Recognition](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)
- 36 classes (e.g., apple, banana, tomato, cabbage, corn, etc.)
- 3 subfolders:
  - `train` – 100 images per class
  - `test` – 10 images per class
  - `validation` – 10 images per class

---

## 🧪 Methodology

- Used `image_dataset_from_directory` for loading and preprocessing
- Applied CNN layers:
  - Convolution + ReLU + MaxPooling
- Training done on Google Colab
- Evaluation done using accuracy and loss plots

---

## 🖼️ Results

- 🧠 Achieved high validation accuracy
- 📉 Low overfitting with proper dropout and batch normalization
- 📈 Real-time testing accuracy verified on test set

---


