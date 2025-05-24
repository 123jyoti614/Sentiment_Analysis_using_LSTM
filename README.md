# Sentiment_Analysis_using_LSTM
This project focuses on classifying movie reviews as positive or negative using deep learning. It leverages a Long Short-Term Memory (LSTM) neural network to capture long-term dependencies in natural language.
# 🎬 Movie Review Sentiment Analysis using LSTM

This project aims to classify movie reviews as **positive** or **negative** using an LSTM-based deep learning model. The model is trained on the IMDb dataset and is capable of capturing long-term dependencies in text to accurately predict sentiment.

---

##  Dataset

- **Size**: 50,000 reviews (25k for training, 25k for testing)
- **Classes**: Positive / Negative (Binary Sentiment Classification)

---

##  Project Pipeline

1. **Text Cleaning & Preprocessing**
   - Lowercasing, removing HTML tags and punctuation
   - Tokenization and padding
   - Removing stopwords

2. **Model Architecture**
   - Embedding layer
   - LSTM (Long Short-Term Memory) layer
   - Dense layers with sigmoid activation for binary classification

3. **Training**
   - Binary Cross-Entropy loss
   - Adam optimizer
   - Trained on 25,000 labeled samples

4. **Evaluation**
   - Accuracy, Precision, Recall, F1 Score
   - Confusion Matrix and Classification Report
   - Plotting training & validation loss and accuracy

---

## 📈 Results

- **Test Accuracy**: ~88%
- The model performs well in distinguishing between positive and negative reviews.
- Generalizes well on new data.

---

##  Technologies Used

- Python
- TensorFlow / Keras
- NumPy / Pandas
- Matplotlib / Seaborn
- NLTK

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-lstm
   cd sentiment-analysis-lstm
