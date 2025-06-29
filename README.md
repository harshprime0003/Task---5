# 🚗 Traffic Accident Data Analysis (Task 5)

This project analyzes **US traffic accident data** to identify key patterns related to:
- Road conditions
- Weather conditions
- Time of day
- Accident severity  
and more.

The goal is to **visualize accident trends** using graphs, word clouds, and uncover contributing factors using a real-world dataset.

---

## 📁 Dataset Used

Dataset source: [US Accident EDA by Harshal Bhamare (Kaggle)](https://www.kaggle.com/code/harshalbhamare/us-accident-eda)

File used: `US_Accidents_Dataset.csv`  
Sample features:
- `Start_Time`, `City`, `State`
- `Severity`, `Weather_Condition`
- `Humidity`, `Temperature`, `Visibility`

---

## 📊 Features / Analysis Performed

- ✔️ Accident severity distribution  
- ✔️ Accidents by hour of day  
- ✔️ Accidents by day of the week  
- ✔️ Top 5 weather conditions  
- ✔️ WordCloud for most common weather during accidents

Each chart is clean, spaced, and fully visualized using `matplotlib`, `seaborn`, and `wordcloud`.

---

## ▶️ How to Run This Project

1. Open this notebook in **Google Colab**
2. Upload the file `US_Accidents_Dataset.csv`
3. Run all cells (Ctrl + F9)
4. View the visual outputs and WordCloud

If WordCloud gives an error, install it using:
```bash
!pip install wordcloud
