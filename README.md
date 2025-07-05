# 📺 Netflix Content Analysis Project

Welcome to the **Netflix Content Analysis Project**, an individual **Exploratory Data Analysis (EDA)** initiative focused on uncovering meaningful insights from Netflix’s content catalog. With over **7,700+** entries of movies and TV shows, this project explores patterns in content type, genre, country distribution, and temporal trends to support strategic decisions in the OTT space.

---

## 📌 Project Objective

To analyze Netflix's streaming content data to:

* Understand content distribution and viewer trends.
* Identify regional contributions and genre preferences.
* Extract actionable insights for strategic content planning, audience targeting, and regional expansion.

---

## 🧾 Dataset Overview

* **Source:** [Netflix Dataset](#)
* **Total Entries:** 7,787
* **Key Features:**

  * `title`, `director`, `cast`, `country`
  * `release_year`, `date_added`, `duration`, `rating`, `listed_in` (genres)

---

## 🧹 Data Preprocessing

* **Missing Values** handled in key columns like `director`, `cast`, and `country`.
* **Datetime Conversion**: `date_added` converted to datetime; extracted `year_added` and `month_added`.
* **Duration Split**: `duration` was split into:

  * `duration_int` (numeric)
  * `duration_type` (categorical: "min"/"Seasons")

---

## 📊 Key Visualizations & Insights

### 1. **Content Type Distribution**

* 📈 *Movies* dominate over TV Shows.
* 💡 Insight: Opportunity to boost long-form content for engagement.

### 2. **Country-wise Content Contribution**

* 🇺🇸 USA leads in content production, followed by 🇮🇳 India and 🇬🇧 UK.
* 💡 Regional content strategy is essential for global expansion.

### 3. **Genre Preferences**

* 🎭 Most frequent genres: Drama, Comedy, International Movies.
* 💡 Diversification into underrepresented genres may help retain diverse audiences.

### 4. **Temporal Trends in Releases**

* 📉 Peak releases during 2015–2019; dip post-2020 (pandemic effect).
* 💡 Helps anticipate future slowdowns and adjust pipelines.

### 5. **Monthly Content Additions**

* 📅 Peaks in October & December, aligning with holiday viewership.
* 💡 Netflix follows seasonal content release strategy.

### 6. **Movie Duration Distribution**

* ⏱️ Most movies range between 80–120 minutes.
* 💡 Content aligns with traditional viewing preferences.

### 7. **Content Rating Distribution**

* 🔞 Dominance of TV-MA & TV-14 rated content.
* 💡 Strong focus on mature/teen audience; scope for more children’s content.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Jupyter Notebook**

---

## 📁 Folder Structure

```
Netflix-Content-Analysis-Project/
│
├── data/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── Netflix_EDA.ipynb
│
├── images/
│   └── [All generated graphs and plots]
│
├── README.md
└── requirements.txt
```

---

## 📈 Future Scope

* Integrate IMDb or Rotten Tomatoes scores for deeper quality analysis.
* Apply NLP for plot summaries and genre clustering.
* Build a recommendation system based on user preferences.

---

## 📬 Contact

For any queries or suggestions, feel free to reach out:

**Isha Chaudhary**

📧 [ishadvay3928@gmail.com]

🔗 [LinkedIn](https://www.linkedin.com/in/ishachaudhary18/)

📍 Noida, India


