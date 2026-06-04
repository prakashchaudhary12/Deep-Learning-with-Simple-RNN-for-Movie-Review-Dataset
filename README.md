# 🎬 IMDB Movie Review Sentiment Analysis using Simple RNN

This project performs sentiment analysis on IMDB movie reviews using a Deep Learning model built with TensorFlow and Keras. A Simple Recurrent Neural Network (Simple RNN) is trained to classify movie reviews as **Positive** or **Negative**. The trained model is deployed using **Streamlit** for interactive predictions.

## 📌 Project Overview

The project consists of:

- Data preprocessing using the IMDB dataset
- Word embedding and sequence padding
- Building and training a Simple RNN model
- Saving the trained model
- Loading the model for inference
- Streamlit web application for real-time sentiment prediction

## 📂 Project Structure

```
├── simplernn.ipynb          # Model training notebook
├── prediction.ipynb         # Model inference notebook
├── embedding.ipynb          # Word embedding examples
├── main.py                  # Streamlit application
├── simple_rnn_imdb.h5       # Trained RNN model
├── requirements.txt         # Required dependencies
└── README.md                # Project documentation
```

## 🧠 Model Architecture

- Embedding Layer
- SimpleRNN Layer
- Dense Output Layer (Sigmoid Activation)

The model predicts whether a movie review expresses a positive or negative sentiment.

## 📊 Dataset

The project uses the **IMDB Movie Review Dataset** provided by TensorFlow/Keras.

Features:
- 50,000 movie reviews
- Binary sentiment classification
- Preprocessed and integer-encoded reviews

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd imdb-sentiment-analysis
```

### 2. Create Virtual Environment

```bash
python -m venv .venv
```

Activate environment:

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/Mac**

```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 🚀 Running the Application

Start the Streamlit application:

```bash
streamlit run main.py
```

Open the URL shown in the terminal (usually):

```text
http://localhost:8501
```

## 📝 Usage

1. Enter a movie review in the text box.
2. Click **Classify**.
3. The application will display:
   - Sentiment (Positive / Negative)
   - Prediction Score

### Example

**Input:**

```text
This movie was amazing. The acting and storyline were excellent.
```

**Output:**

```text
Sentiment: Positive
Prediction Score: 0.94
```

## 📦 Dependencies

- TensorFlow
- NumPy
- Pandas
- Scikit-Learn
- TensorBoard
- Matplotlib
- Streamlit
- SciKeras

## 🔍 Notebooks Description

### simplernn.ipynb
- Loads IMDB dataset
- Preprocesses text data
- Builds and trains Simple RNN model
- Evaluates model performance
- Saves trained model

### prediction.ipynb
- Loads saved model
- Preprocesses user reviews
- Predicts sentiment

### embedding.ipynb
- Demonstrates one-hot encoding
- Explains word embeddings and text representation

## 📈 Future Improvements

- Replace Simple RNN with LSTM or GRU
- Hyperparameter tuning
- Deploy on Streamlit Cloud
- Add model performance visualizations
- Support custom datasets

## 👨‍💻 Author

Prakash Kumar Chaudhary

---

⭐ If you found this project useful, consider giving it a star.
