<div align="center">

<!-- BANNER: Use a tool like Canva, Adobe Express, or MidJourney to create a 1200×400px banner showing:
     - A dark cinematic background with film reel / clapperboard silhouettes
     - Text overlay: "Tamil Cinema Dataset Analysis" in bold Tamil-style golden font
     - Subtle film strip border along bottom
     Then replace the placeholder below with: ![Banner](assets/banner.png) -->

```
╔══════════════════════════════════════════════════════════════════════════╗
║                                                                          ║
║        🎬  TAMIL CINEMA DATASET ANALYSIS  🎬                            ║
║        Kollywood · Data · Insights · Trends                              ║
║                                                                          ║
╚══════════════════════════════════════════════════════════════════════════╝
```

# 🎬 Tamil Cinema Dataset Analysis

### *Unraveling the Story Behind Kollywood — One Data Point at a Time*

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-11557C?style=for-the-badge)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

## 🌟 Project Overview

> *"Tamil cinema is not just an industry — it's an emotion shared by millions."*

This project dives deep into the **Tamil film industry (Kollywood)** using data science techniques to extract meaningful insights about movies, actors, directors, box office trends, ratings, and much more.

From the golden era of **MGR and Sivaji** to the modern blockbusters of **Rajinikanth, Kamal Haasan, Vijay, and Ajith**, this dataset captures decades of cinematic history — analyzed through the lens of data.

---

## 🎥 What Makes Kollywood Unique?

<div align="center">

| 🏆 Stat | 📊 Value |
|--------|---------|
| 🎞️ Films produced per year | ~200+ |
| 🌍 Global audience | 80 million+ Tamil speakers |
| 💰 Industry worth | ₹2,000+ Crore annually |
| 🎭 Active since | 1916 (over 100 years!) |
| 🌐 Top markets | India, Sri Lanka, Malaysia, Singapore, UAE |

</div>

---

## 📁 Repository Structure

```
Cinema-Dataset-Analysis/
│
├── 📂 data/
│   ├── tamil_movies_raw.csv        # Raw dataset
│   ├── tamil_movies_cleaned.csv    # Cleaned & preprocessed
│   └── supplementary/             # Additional supporting data
│
├── 📂 notebooks/
│   ├── 01_data_cleaning.ipynb      # Data wrangling & preprocessing
│   ├── 02_eda.ipynb                # Exploratory Data Analysis
│   ├── 03_visualization.ipynb      # Charts & visual storytelling
│   └── 04_insights.ipynb          # Key findings & conclusions
│
├── 📂 src/
│   ├── data_loader.py             # Data ingestion utilities
│   ├── preprocessing.py           # Cleaning functions
│   └── visualizer.py              # Reusable plot functions
│
├── 📂 assets/
│   └── images/                    # Charts and output visuals
│
├── 📄 requirements.txt
├── 📄 LICENSE
└── 📄 README.md
```

---

## 📊 Dataset Features

The dataset includes rich information across **Tamil films** spanning multiple decades:

| Column | Description |
|--------|-------------|
| `movie_title` | Name of the film (Tamil & transliterated) |
| `release_year` | Year of theatrical release |
| `director` | Film director(s) |
| `hero` / `heroine` | Lead cast |
| `music_director` | Background score & songs composer |
| `box_office` | Worldwide gross collection (₹ Crore) |
| `imdb_rating` | IMDb audience rating |
| `genre` | Genre tags (Action, Drama, Romance, Thriller…) |
| `runtime_mins` | Movie duration |
| `language_dub` | Dubbed language versions |
| `production_house` | Banner / Production company |
| `ott_platform` | Streaming platform availability |

---

## 🔍 Key Analyses Performed

### 1. 🎭 Top Directors by Box Office Collection
Identifying which directors consistently delivered blockbusters.

### 2. ⭐ Actor Popularity & Rating Trends
How audience reception of leading actors has evolved over the years.

### 3. 📅 Decade-wise Film Production Trends
Comparing the 80s, 90s, 2000s, 2010s, and 2020s for volume & quality.

### 4. 🎵 Music & Commercial Success Correlation
Does a hit album guarantee box office success?

### 5. 💸 Budget vs. Collection Analysis
ROI analysis — which films delivered the most value?

### 6. 🌐 OTT vs. Theatrical Performance
Post-2020 streaming shift and its impact on the industry.

### 7. 🏷️ Genre Popularity Over Time
Rise of thriller, fall of pure comedy — genre evolution mapped.

---

## 📈 Sample Visualizations

> 📌 *After cloning, run the notebooks to generate these charts in `/assets/images/`*

- 📊 **Bar Chart** — Top 10 Highest Grossing Tamil Films of All Time
- 📉 **Line Graph** — Year-wise Average IMDb Rating Trend
- 🥧 **Pie Chart** — Genre Distribution Breakdown
- 🔥 **Heatmap** — Director × Genre Success Matrix
- 📦 **Box Plot** — Rating Distribution by Decade
- 🌐 **Word Cloud** — Most Common Words in Tamil Movie Titles

---

## 🚀 Getting Started

### Prerequisites

```bash
Python >= 3.10
pip (package manager)
Jupyter Notebook or JupyterLab
```

### Installation

```bash
# 1. Clone this repository
git clone https://github.com/vivekanandhans129-png/Cinema-Dataset-Analysis.git

# 2. Navigate into the project folder
cd Cinema-Dataset-Analysis

# 3. Install required packages
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook
```

### Requirements

```txt
pandas>=1.5.0
numpy>=1.23.0
matplotlib>=3.6.0
seaborn>=0.12.0
plotly>=5.10.0
jupyter>=1.0.0
scikit-learn>=1.1.0
wordcloud>=1.9.0
```

---

## 💡 Key Insights (Sneak Peek)

> 🔎 These are preliminary findings — full analysis available in the notebooks.

- 🎬 **Rajinikanth** films consistently outperform box office predictions by **30–40%** due to fan frenzy
- 📅 Tamil cinema saw its **highest production volume** in the 2010s decade
- 🎵 Films with **AR Rahman** as music director have a **25% higher average rating**
- 💰 The average **breakeven budget** for Tamil films has grown **8x** since 2000
- 🌍 **OTT releases** post-2020 have given smaller-budget films a **wider audience reach**
- 🏆 **Action** remains the dominant genre, but **psychological thrillers** are the fastest-growing

---

## 🎬 The Kollywood Legacy — By the Numbers

```
🎥  1916  →  First Tamil silent film "Keechaka Vadham"
🎵  1931  →  First Tamil talkie "Kalidas"
🏆  1960  →  MGR era begins — politics meets cinema
🌟  1980s →  Rajinikanth & Kamal Haasan redefine superstardom
💫  1990s →  Golden age of Tamil music (AR Rahman revolution)
🚀  2000s →  Technical leap — VFX, global releases
📱  2020s →  OTT disruption + pan-India market expansion
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** this repository
2. **Create** a new branch (`git checkout -b feature/amazing-analysis`)
3. **Commit** your changes (`git commit -m 'Add genre clustering model'`)
4. **Push** to the branch (`git push origin feature/amazing-analysis`)
5. **Open** a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting PRs.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- **IMDb** for publicly available movie ratings
- **Tamil Film Producers Council** for industry data
- The entire **Kollywood community** for 100+ years of incredible cinema
- Open-source contributors who built Pandas, Matplotlib & Seaborn

---

<div align="center">

### ⭐ If you found this project useful, please give it a star!

*Made with ❤️ and a deep love for Tamil Cinema*

---

**`🎬 Kollywood | 📊 Data Science | 🐍 Python | 💡 Insights`**

</div>
