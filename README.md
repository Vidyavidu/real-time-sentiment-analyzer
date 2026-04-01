# Real-Time Social Media Sentiment Analyzer 

##  Project Overview
This project is a **Real-Time Sentiment Analysis System** that analyzes text data (like social media posts) and classifies it into:
- Positive 😊
- Negative 😡
- Neutral 😐

It helps in understanding public opinion, customer feedback, and trending sentiments in real-time.

---

## Objectives
- Analyze sentiment of text data
- Classify text into positive, negative, or neutral
- Simulate real-time sentiment analysis
- Visualize results using graphs
- Provide a simple user interface

---

##  Technologies Used
- **Python** – Core programming language  
- **VADER Sentiment Analyzer** – Sentiment analysis  
- **Matplotlib** – Data visualization  
- **Streamlit** – Web application interface  

---

##  How It Works
1. **Input Collection**
   - User enters text (simulating social media posts)

2. **Preprocessing**
   - Text is cleaned and prepared

3. **Sentiment Analysis**
   - VADER analyzes sentiment scores

4. **Classification**
   - Positive (≥ 0.05)  
   - Negative (≤ -0.05)  
   - Neutral (-0.05 to 0.05)

5. **Visualization**
   - Results displayed using graphs

---

##  Example Output

| Text                          | Sentiment |
|-------------------------------|----------|
| I love this IPL match         | Positive |
| This movie is terrible        | Negative |
| AI is changing the world      | Positive |
| I am not happy with results   | Negative |
| This is okay                  | Neutral  |

---

##  Result Visualization
- Bar charts show distribution of sentiments
- Helps quickly understand overall opinion trends

---

##  How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/your-username/real-time-sentiment-analyzer.git
