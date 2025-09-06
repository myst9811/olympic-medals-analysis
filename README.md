# 🏅 Olympic Medal Analysis

## 📌 Project Overview

This project analyzes **120 years of Olympic history (1896–2016)** using the official Kaggle dataset. The analysis explores medal tallies, participation trends, gender diversity, and country-wise performance using Python data analysis libraries.

## 📊 Dataset

**Source**: [120 years of Olympic history: athletes and results](https://www.kaggle.com/datasets/mysarahmadbhat/120-years-of-olympic-history-athletes-and-results)

**Files**:

- `athlete_events.csv` – Athlete-level information (Name, Sex, Age, Team, Sport, Event, Medal)
- `noc_regions.csv` – Mapping of National Olympic Committee (NOC) codes to countries/regions

## ⚙️ Tech Stack

- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Google Colab (with Google Drive integration)

## 📊 Features & Analysis

### 1. Data Cleaning & Merging

- Handled missing values in Age, Height, Weight, Medal
- Merged `athlete_events.csv` with `noc_regions.csv`

### 2. Medal Tally

- Overall medal tally (all-time)
- Year-wise medal tally by country
- Saved medal tallies to `outputs/medal_tally.csv`

### 3. Trends Over Time

- Number of participating nations per Olympics
- Number of athletes per Olympics
- Events growth across decades

### 4. Gender Participation

- Male vs Female athlete participation trends
- Plots showing the evolution of gender diversity

### 5. Country Analysis

- India's medal tally over the years
- USA, China, Russia medal dominance
- Heatmap of country-year medals

### 6. Top Athletes

- Most decorated athletes (e.g., Michael Phelps)
- Sport-wise top performers

## 📈 Visualizations

- Line plots of participation trends
- Bar charts for medal tallies
- Heatmaps for country-year medals
- Gender participation comparison

_Plots are generated using Matplotlib & Seaborn and displayed directly in the notebook._

## 📂 Project Structure

```
olympic-medal-analysis/
│
├── 📂 data/
│   ├── athlete_events.csv
│   └── noc_regions.csv
│
├── 📂 outputs/
│   └── medal_tally.csv
│
├── 📜 Olympic_Analysis.ipynb    # main notebook
├── 📜 README.md                # project documentation
└── 📜 requirements.txt         # Python dependencies
```

## 🚀 Usage

1. Open the project in Google Colab
2. Upload the dataset files to the `data/` folder
3. Run the `Olympic_Analysis.ipynb` notebook
4. View generated visualizations and analysis results
5. Check the `outputs/` folder for saved CSV files
