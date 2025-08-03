
# ✈️ BA_AirlineReviews – Sentiment Analysis Project

## Overview
BA_AirlineReviews is a Natural Language Processing (NLP) project that performs sentiment analysis on airline passenger reviews. The system is designed to automatically classify user reviews as either **positive** or **negative** using machine learning techniques and a Streamlit web interface.

## Features
- Classifies airline reviews based on sentiment polarity.
- Cleans and preprocesses raw text data.
- Uses TF-IDF vectorization for feature extraction.
- Supports multiple machine learning models (e.g., Logistic Regression, Naive Bayes).
- Interactive Streamlit interface for real-time prediction.

## Technologies Used
- **Python**
- **Streamlit**
- **Scikit-Learn**
- **Pandas**
- **NumPy**
- **NLTK / spaCy** (optional for preprocessing)
- **Matplotlib / Seaborn** (for EDA and visualization)

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/BA_AirlineReviews-Sentiment-Analysis.git
   cd BA_AirlineReviews-Sentiment-Analysis
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Enter or paste a review in the text input box.
2. Click the **Analyze Sentiment** button.
3. The model will return whether the review is **Positive** or **Negative**.

## Dataset
The dataset contains labeled airline passenger reviews sourced from public airline review platforms, including text comments and sentiment labels.

## Future Enhancements
- Add support for more granular sentiment (e.g., neutral, mixed).
- Train with deep learning models (e.g., LSTM or BERT).
- Deploy as a REST API for wider integration.

---

**Author:** Muhammed-AlReay  
**Note:** This is a fully modular and customizable NLP project suitable for production or academic use.
