# text-classification-tensorflow
# 🎬 Text Classification with TensorFlow on IMDb Movie Reviews

This project demonstrates how to build a text classification model using **TensorFlow** and the **IMDb movie reviews dataset**. The goal is to classify movie reviews as **positive** or **negative** using a binary sentiment analysis approach.

## 📌 Project Overview

- **Dataset**: IMDb Movie Reviews (50,000 reviews split equally between train and test)
- **Task**: Binary text classification (sentiment analysis)
- **Framework**: TensorFlow (Keras API)
- **Model**: Sequential neural network with Embedding and LSTM/Dense layers
- **Evaluation Metric**: Accuracy

## 📂 Files

- `text_classification_imdb.ipynb` – Jupyter Notebook containing the full workflow: preprocessing, model training, evaluation, and predictions.

## 🧠 Key Features

- Tokenization and padding of text data
- Embedding layer for word representation
- Recurrent/Dense layers for learning text patterns
- Accuracy and loss visualization
- Model evaluation on test data

## 📊 Sample Output

- Train Accuracy: ~95%  
- Test Accuracy: ~88-90% (depending on hyperparameters)

## ⚙️ Requirements

Install the required Python libraries using:

```bash
pip install -r requirements.txt

