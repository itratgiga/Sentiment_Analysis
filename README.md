# Sentiment Analysis on Product Reviews

## 📌 Project Overview
This project performs **Sentiment Analysis** on Amazon product reviews using **Natural Language Processing (NLP)** techniques. The main objective is to automatically classify customer reviews into:

- 😊 Positive
- 😡 Negative
- 😐 Neutral

The project helps businesses understand customer opinions and improve products based on customer feedback.

---

## 🎯 Problem Statement
E-commerce platforms receive thousands of customer reviews daily. Manually analyzing these reviews is time-consuming and inefficient. This project automates the process by analyzing review text and identifying customer sentiment.

---

## 📂 Dataset
Dataset used: **Amazon Fine Food Reviews**

Source: Kaggle  
Dataset Link:  
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

- File Used: `Reviews.csv`
- Rows Used: First 5000 rows

---

## 🛠 Technologies & Libraries Used

| Tool / Library | Purpose |
|----------------|---------|
| Python | Main programming language |
| Jupyter Notebook | Code execution |
| Pandas | Data loading & cleaning |
| TextBlob | Sentiment Analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |

---

## 📋 Project Workflow

### 1. Data Loading
- Loaded dataset using Pandas
- Selected first 5000 rows

### 2. Data Cleaning
- Removed null values
- Removed duplicate reviews
- Selected required columns:
  - `Text`
  - `Score`

### 3. Sentiment Analysis
Used TextBlob to calculate sentiment polarity:
- Positive → score > 0
- Negative → score < 0
- Neutral → score = 0

### 4. Data Visualization
Created:
- 📊 Bar Chart
- 🥧 Pie Chart
- 📈 Word Frequency Chart

### 5. Insights Generation
Analyzed customer feedback and identified common issues in negative reviews.

---

## 📊 Visualizations

### Distribution of Customer Sentiments
- Shows count of Positive, Negative, and Neutral reviews.

### Percentage Distribution
- Shows sentiment percentages using a pie chart.

### Word Frequency Analysis
- Displays most common words used in negative reviews.

---

## 💡 Key Insights

- Most customer reviews were positive.
- Negative reviews mainly mentioned:
  - Product quality issues
  - Poor packaging
  - Bad taste
- Some reviews showed mismatch between ratings and written sentiment.

---

## 🚀 Future Improvements

This project can be improved by:
- Using Machine Learning models
- Applying Deep Learning / NLP techniques
- Improving sentiment accuracy
- Adding live dashboard visualization

---

## ✅ Conclusion

This project demonstrates how sentiment analysis can be used to extract meaningful insights from customer reviews. It helps businesses understand customer satisfaction and improve products based on feedback.

---

## 👩‍💻 Author

**Itrat Zehra Giga**

```
