# 📊 Netflix Content Strategy — Exploratory Data Analysis

An end-to-end EDA project exploring the Netflix Movies and TV Shows dataset
to uncover patterns in content strategy, geographic diversity, and library
trends over time.

---

## 📁 Dataset

- **Source:** [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Size:** 8,807 titles × 12 columns
- **Coverage:** Titles added to Netflix up to mid-2021
- **Key columns:** `type`, `title`, `director`, `country`, `date_added`,
  `release_year`, `rating`, `duration`, `listed_in`

---

## ❓ Questions Explored

### 🔎 Data Quality
1. What is the distribution of Movies and TV Shows?
2. Why is the `director` field missing for ~30% of titles?
3. How clean is the `duration` column?

### 📅 Time Trends
4. How has Netflix's content library grown over time?
5. How has the Movie / TV Show ratio shifted year by year?
6. Which month sees the most new content added?
7. Does Netflix favour newer or older content, and has this changed?

### 🌍 Country & Diversity
8. Which countries specifically produce TV Shows on Netflix?
9. Is international content growing as a share of total additions?

### 🎬 Content Analysis
10. What is the average movie duration, and has it changed?
11. What genres dominate in specific countries?

---

## 🔑 Key Findings

- **Movies dominate** (~70% of catalog) but the TV Show share of annual
  additions has grown from ~25% in 2013 to ~35% by 2021
- **January** is Netflix's biggest content month; **February** is the quietest
- **Content age at addition** dropped sharply after 2016, driven by Netflix
  Originals (content age = 0)
- **International content crossed 50%** of annual additions by 2019 — Netflix
  is no longer a US-centric platform
- **South Korea and Japan** are disproportionately TV Show-heavy, reflecting
  the global popularity of K-dramas and anime
- **Average movie duration** has stayed stable at ~90–100 minutes — no
  evidence of a "streaming shortening" effect

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data loading, cleaning, transformation |
| Matplotlib | Base plotting |
| Seaborn | Statistical visualisations |
| Jupyter Notebook | Interactive analysis environment |

---

## 🚀 How to Run

1. Clone the repository
```bash
   git clone https://github.com/Saurabh6266/EDA_on_Netflix_Movies_and_TV_Shows
   cd EDA_on_Netflix_Movies_and_TV_Shows
```

2. Install dependencies
```bash
   pip install pandas matplotlib seaborn jupyter
```

3. Launch the notebook
```bash
   jupyter notebook eda_netflix.ipynb
```

4. Run all cells top to bottom (Kernel → Restart & Run All)

---

## 📂 Project Structure
```
EDA_on_Netflix_Movies_and_TV_Shows/
│
├── eda_netflix.ipynb      ← Main analysis notebook
├── netflix_titles.csv     ← Dataset (from Kaggle)
├── requirements.txt       ← Python dependencies
└── README.md              ← This file
```

---

## 👤 Author

**Saurabh** — [GitHub Profile](https://github.com/Saurabh6266)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).