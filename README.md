
# 🚗 Tesla Stock Prediction App

This project is an interactive web app that predicts **Tesla stock price changes** based on the **sentiment of tweets**. Users can input a tweet (real or hypothetical), and the app will analyze its sentiment and estimate the resulting impact on Tesla’s stock price.

Built as a **collaborative team project** using **Python**, **Flask**, **RoBERTa** for sentiment analysis, and **XGBoost** for regression-based stock movement prediction.

---

🔍 Overview

This app explores the influence of social media on stock market behavior — specifically how tweet sentiment can correlate with Tesla’s price shifts. It combines **natural language processing (NLP)** and **machine learning** in an end-to-end pipeline built for web-based interaction.

---

👥 Collaboration

This project was developed as part of a team, where we collaborated on data sourcing, model training, and Flask integration. My individual contributions focused on:
- Developing the **XGBoost regression pipeline**
- Building and styling the **Flask web interface**
- **Data cleaning and feature engineering**

---

🧠 Key Features

- **Tweet Input Form**  
  Enter any Tesla-related tweet to receive a predicted percent change in stock price.

- **RoBERTa Sentiment Analysis**  
  Uses `cardiffnlp/twitter-roberta-base-sentiment` to classify tweet tone.

- **XGBoost Regression Model**  
  Trained on sentiment and engagement metrics (likes, retweets, replies).

- **Interactive Web Interface**  
  Built with Flask for real-time input/output.

- **Visuals**  
  Dashboard tabs with visuals showcasing tweets & stock relationships and statistics.
---

🧰 Tech Stack

- **Frontend**: HTML, Bootstrap  
- **Backend**: Python, Flask  
- **ML/NLP**: Hugging Face Transformers (RoBERTa), XGBoost  
- **Data Processing**: Pandas, NumPy  





