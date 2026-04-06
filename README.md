# 🎬 Netflix Content Analysis (Tableau)

## 📌 Project Overview
This project involves a comprehensive analysis of the Netflix catalog using Tableau. The goal was to transform raw data into an interactive dashboard that reveals content trends, genre popularity, and production insights over time.

**🔗 [View the Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/nazeeb.ullah/viz/Netflix_17736216514120/Netflix)**

## 📊 Dashboard Snapshot
![Netflix Dashboard](<img width="640" height="443" alt="Screenshot 2026-04-07 001756" src="https://github.com/user-attachments/assets/982a8720-63f2-42cf-b2a4-9071fe3b705e" />)

## 💡 Key Insights & Data Findings
Based on the visualizations created, several key trends were identified:
* **Genre Dominance:** **Dramas** are the most prevalent genre on the platform with **3,180 titles**, significantly outperforming other categories like Family (1,084) and Documentaries (867).
* **Production Volume:** There was a massive surge in content added to the platform between 2016 and 2019, peaking just before 2020.
* **Content Metrics:** For the filtered "Movie" category, the average movie length on the platform is exactly **100 minutes**, suggesting a standardized runtime preference for streaming audiences.
* **Interactivity:** The dashboard includes global filters for **Release Year** and **Director**, allowing users to drill down into specific production eras or creator portfolios.

## 🛠️ Technical Skills Demonstrated
* **Data Cleaning & Prep:** Handled "Null" date values and ensured proper data types for time-series analysis.
* **Calculated Fields:** Authored complex `IF CONTAINS` logic to create custom Boolean genre flags (e.g., grouping 'Kids', 'Children', and 'Family' into a single category).
* **Advanced Formatting:** Implemented **Measure Names and Measure Values** to create synchronized horizontal bar charts.
* **Interactive Design:** Configured global dashboard filters and customized tooltips for a better user experience.

## 📁 Files & Data Source
* **Data Source:** [View the raw Netflix Dataset here (Google Sheets)](https://docs.google.com/spreadsheets/d/1YmZKhB5gOYoB5LzlayIKg5qhFH4mp_uD9lINULsjhoQ/edit?gid=0#gid=0)
* `Netflix.twbx`: The packaged Tableau workbook containing the backend build and visualizations.
* `Dashboard_Snapshot.png`: A high-resolution image of the final dashboard.
