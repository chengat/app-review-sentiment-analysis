---

# 📱 Senior-Focused App Review Analysis  

This repository contains a **data analysis project** that collects, preprocesses, and analyzes reviews of senior-focused Android apps from the **Google Play Store**. The project uses NLP techniques for **sentiment analysis**, **topic modeling**, and **feature brainstorming** to better understand how elderly users interact with mobile applications and what improvements can be made.

---

## 🚀 Features

- **Data Collection**
  - Scrapes app details and user reviews using [`google-play-scraper`](https://pypi.org/project/google-play-scraper/).
  - Supports fetching thousands of reviews across multiple senior-focused apps.

- **Preprocessing**
  - Cleans text (whitespace, punctuation, emojis).
  - Converts numbers to words.
  - Removes stop words.
  - Lemmatizes tokens for normalization.

- **Sentiment Analysis**
  - Multiple sentiment models compared:
    - [TextBlob](https://textblob.readthedocs.io/en/dev/)  
    - [VADER](https://github.com/cjhutto/vaderSentiment)  
    - LLM-based classification via **Groq API (LLaMA models)**  

- **Topic Modeling**
  - Uses **Latent Dirichlet Allocation (LDA)** to extract themes from reviews.
  - Highlights common complaints like ads, usability, and accessibility.

- **GPT for Brainstorming**
  - Prompts GPT to act as a stakeholder (e.g., an elderly user or a developer).
  - Provides design recommendations for improving app usability for seniors.

---

## 📊 Example Insights

- Many users complain about **intrusive advertisements**.  
- Elderly users request **larger icons, dark mode, and higher text contrast**.  
- Positive reviews highlight **simplicity and ease of navigation**.  
- LDA Topic Modeling clusters issues into usability, accessibility, and monetization.

---
