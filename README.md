# 🧠 Age Prediction from Face Images using CNN

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow** to predict a person's age based on facial images. It uses a portion of the training data and evaluates performance on a separate validation set. The model is trained and tested on Google Colab using images stored on Google Drive.

---

## 📁 Dataset Structure

The dataset must be stored in the following directory structure inside your Google Drive:


Each image filename should start with the person's **age**, followed by an underscore (`_`) and any name (e.g., `23_john.jpg`).

---

## 🧪 Features

- Loads a subset (20%) of training images randomly for quick experimentation.
- Loads all validation images.
- Normalizes pixel values to `[0, 1]`.
- Trains a simple CNN architecture to predict age (regression task).
- Uses `Mean Absolute Error (MAE)` as both the loss function and evaluation metric.
- Uses `EarlyStopping` to prevent overfitting.
- Supports single image prediction and visualization.
- Plots training and validation loss curves.

---

## 🛠️ Tech Stack

- Python
- TensorFlow (Keras API)
- OpenCV
- Matplotlib
- Google Colab
- Google Drive

---

## 🧠 Model Architecture


_A visualization of the image with predicted age will also be shown._

---

## 📝 Notes

- You can easily scale up by removing the sampling step in `load_subset()` and loading the full training dataset.
- Increase input resolution or modify architecture for better performance on more complex datasets.

---

## 📌 Author

**Yassin Ehab Farouk Mostafa Mostafa**  
CS Student | Machine Learning Enthusiast

---

## 📜 License

This project is for educational and academic purposes. You are free to modify and use it as needed.
