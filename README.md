# 🎵 Music Streaming Website Traffic Analysis Dashboard

## 📌 Overview
This project analyzes music streaming clickstream data to understand user behavior, traffic trends, artist popularity, and geographic distribution. Using Python, Pandas, and Matplotlib, the project transforms raw event data into a comprehensive visual analytics dashboard.

## 📂 Dataset Description
The dataset (`traffic.csv`) contains user click events with the following columns:

| Column | Description |
|------|------------|
| event | Type of event (click) |
| date | Date of the event |
| country | User country |
| city | User city |
| artist | Artist name |
| album | Album name |
| track | Track name |
| isrc | Track identifier (ISRC code) |
| linkid | Unique link identifier |

## 🧹 Data Cleaning & Processing
The project includes the following preprocessing steps:
- Standardizing column names
- Handling missing values with meaningful defaults
- Converting date strings to datetime format
- Extracting day-of-week information for trend analysis

## 📊 Dashboard Visualizations
The dashboard provides insights through:
- Daily Traffic Trend (clicks per day)
- Top 8 Artists by total clicks
- Top 8 Countries by traffic volume
- Traffic by Day of Week
- User Engagement Frequency distribution
- Artist Concentration (Top 5 vs Others)

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Google Colab

## 📌 Key Learnings

* Real-world data cleaning techniques
* Exploratory Data Analysis (EDA)
* Data aggregation using Pandas
* Dashboard creation with Matplotlib

## 🚀 Future Improvements

* Interactive dashboards using Streamlit or Plotly
* Time-series forecasting
* User segmentation and deeper engagement analysis
* Genre and artist trend analysis

## 👤 Author
AZHAR ZUBAIR 
