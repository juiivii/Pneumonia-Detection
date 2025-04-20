# Pneumonia Detection from Chest X-Rays

This project is a deep learning-based approach to detect **pneumonia** from chest X-ray images. It uses Convolutional Neural Networks (CNNs) to classify images as either **Normal** or **Pneumonia-infected**.

The model is trained on a publicly available dataset from Kaggle and includes training visualization, evaluation metrics, and a confusion matrix.

---

## 📁 Dataset

We use the **Chest X-Ray Pneumonia Dataset** from Kaggle:  
🔗 [Chest X-Ray Images (Pneumonia) – Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

The dataset consists of over 5,000 images categorized into:
- Training set
- Validation set
- Test set

> **To download the dataset:**
1. Go to your [Kaggle account settings](https://www.kaggle.com/account) and download your `kaggle.json` API token.
2. Upload the token in the notebook when prompted.
3. The dataset will automatically download and unzip into the working directory.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/juiivii/pneumonia-detection.git
   cd pneumonia-detection

2. Requirements:
  Main Python libraries used:
    TensorFlow / Keras
    NumPy
    Matplotlib
    scikit-learn
    kaggle

  3.Launch the notebook

4. Follow the steps in the notebook to download the dataset and train the model.

Disclaimer: This project is for educational and experimental purposes only and is not intended for actual medical diagnosis.
