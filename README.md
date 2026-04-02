#  Fake Review Detection Using Machine Learning

## Overview
This project focuses on detecting fake product reviews using machine learning. Fake reviews can mislead customers, distort ratings, and reduce trust in online platforms.

The system uses data preprocessing and ML models to classify reviews as real or fake automatically.

---

## Features
- Detect fake vs real reviews  
- Data cleaning and preprocessing pipeline  
- Feature engineering (text length, word count)  
- Machine learning classification  
- Data visualization and insights  

---

## Dataset
- Source: Amazon Customer Reviews dataset  
- Total samples: 40,432  
- Columns:
  - category  
  - rating  
  - label (real / fake)  
  - review text  

Dataset is balanced between real and fake reviews. :contentReference[oaicite:0]{index=0}  

---

## Data Preprocessing

## Cleaning Steps
- Remove duplicates  
- Convert text to lowercase  
- Remove URLs, emojis, punctuation, numbers  
- Normalize text using Unicode  
- Remove very short/long reviews  

## Feature Engineering
- Word length (word_len)  
- Character length (char_len)  

---

## Machine Learning

## Objective
- Train models to classify reviews  
- Identify patterns between real and fake reviews  
- Enable automated detection  

---

## Insights
- Fake reviews are usually shorter and simpler  
- Real reviews are longer and more detailed  
- Balanced dataset improves model performance  

---

## Technologies Used
- Python  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  
- Regular expressions (re)  

---

## Objectives
- Build a clean dataset  
- Train and evaluate ML models  
- Create a system for real-time prediction  

---

## Conclusion
This project demonstrates how machine learning can effectively detect fake reviews by analyzing patterns in text data. It improves trust in online platforms and supports better decision-making for users. :contentReference[oaicite:1]{index=1}  
