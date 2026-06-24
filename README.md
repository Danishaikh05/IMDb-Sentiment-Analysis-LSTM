# IMDb Sentiment Analysis using LSTM

## Overview

This project performs sentiment analysis on IMDb movie reviews using a Long Short-Term Memory (LSTM) neural network. The model classifies reviews as either Positive or Negative based on the review text.

The project demonstrates Natural Language Processing (NLP), text preprocessing, tokenization, sequence padding, and deep learning techniques using TensorFlow and Keras.

---

## Features

- Text preprocessing and cleaning
- Tokenization of movie reviews
- Sequence padding for uniform input length
- LSTM-based deep learning model
- Binary sentiment classification
- Training and evaluation of the model
- Prediction on unseen reviews

---

## Technologies Used

- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

1. Load IMDb dataset
2. Preprocess review text
3. Tokenize reviews
4. Convert text into sequences
5. Apply sequence padding
6. Split data into training and testing sets
7. Build LSTM model
8. Train the model
9. Evaluate performance
10. Predict sentiment of reviews

---

## Model Architecture

- Embedding Layer
- LSTM Layer
- Dense Layer
- Output Layer (Sigmoid Activation)

---

## Results

The model successfully classifies movie reviews into:

- Positive Review
- Negative Review

Performance metrics such as accuracy and loss were used to evaluate the model.

---

## Repository Structure

```
IMDb-Sentiment-Analysis-LSTM/
│
├── Sentiment_Analysis_LSTM.ipynb
├── README.md
└── .gitignore
```

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/Danishaikh05/IMDb-Sentiment-Analysis-LSTM.git
```

### Install Dependencies

```bash
pip install tensorflow pandas numpy scikit-learn matplotlib seaborn
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```
Sentiment_Analysis_LSTM.ipynb
```

and execute all cells.

---

## Future Improvements

- Deploy as a web application using Streamlit
- Improve accuracy using Bidirectional LSTM
- Experiment with GRU and Transformer models
- Add real-time sentiment prediction

---

## Author

**Danish Shaikh**

B.Tech Computer Science and Design

GitHub: https://github.com/Danishaikh05
