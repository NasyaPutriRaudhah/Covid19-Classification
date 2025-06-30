# 🦠 COVID-19 vs Non-COVID Classification using CNN

This project is a part of my computer vision task that implements a **Convolutional Neural Network (CNN)** to classify chest X-ray images into two categories:
**COVID-19** and **Non-COVID**.

## 📂 Project Structure

* `Notebook_Deteksi_COVID_19.ipynb` – Jupyter Notebook containing the full implementation.
* `dataset/` – Folder containing X-ray image data categorized into:

  * `covid/`
  * `non_covid/`

## 🔍 Features

* Preprocessing steps:

  * Resizing images
  * CLAHE (Contrast Limited Adaptive Histogram Equalization)
  * Denoising, sharpening, and gamma correction
* CNN architecture built from scratch
* Evaluation metrics: Accuracy, Precision, Recall, F1-Score
* Visualization:

  * Training history
  * Confusion matrix
  * Sample predictions

## 🧠 Technologies Used

* Python 3.x
* TensorFlow / Keras
* OpenCV
* NumPy, Pandas, Matplotlib
* Scikit-learn

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/NasyaPutriRaudhah/Covid19-Classification.git
   cd Covid19-Classification
   ```

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the notebook:

   ```bash
   jupyter notebook Notebook_Deteksi_COVID_19.ipynb
   ```

## 📊 Sample Results

* Model Accuracy: \~94% 
* Confusion Matrix and other plots available in the notebook

## 📌 Notes

* This is an academic project, not intended for diagnostic or clinical use.
* The dataset is assumed to be organized into two folders: `covid/` and `non_covid/`.

## 👩‍💻 Author

**Nasya Putri Raudhah Dahlan**
Computer Science, Universitas Gadjah Mada
NIM: 23/513931/PA/21967

---

Jika kamu ingin aku bantu membuat `requirements.txt` atau menambahkan visualisasi arsitektur CNN dalam README ini, tinggal bilang ya!
