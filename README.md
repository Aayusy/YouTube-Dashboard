# 📊 YouTube Analytics & Performance Dashboard

An interactive data analytics web application built with **Python** and **Streamlit** to track, analyze, and visualize YouTube channel metrics including views, likes, subscriber growth, video performance over time, and audience comments.

---

## 🚀 Features

* **Interactive Streamlit Interface:** Explore channel performance seamlessly through a clean web UI.
* **Audience & Country Insights:** Track geographic distribution and subscriber sources (`Aggregated_Metrics_By_Country_And_Subscriber_Source.csv`).
* **Video Analytics:** Monitor individual video stats, views, likes, and engagement metrics (`Aggregated_Metrics_By_Video.csv`).
* **Performance Over Time:** Analyze trends and growth patterns across different timeframes (`Video_Performance_Over_Time.csv`).
* **Comment Sentiment & Feedback:** Review viewer comments and feedback in one place (`All_Comments_Final.csv`).

---

## 🛠️️ Tech Stack

* **Language:** Python
* **Framework:** Streamlit
* **Data Processing & Analysis:** Pandas, NumPy

---

## 📂 Project Structure

```text
yt_dashbord/
│
├── Dashboard.py                                     # Main Streamlit application script
├── Aggregated_Metrics_By_Country_And_Subscriber_Source.csv # Country and subscriber data
├── Aggregated_Metrics_By_Video.csv                  # Video performance statistics
├── Video_Performance_Over_Time.csv                  # Time-series performance data
└── All_Comments_Final.csv                           # Viewer comments dataset
