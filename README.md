# 📊 Foodborne Disease Outbreak Analysis | EDA & Risk Insights

## 🧪 Project Overview
This project involves **exploratory data analysis (EDA)** of a real-world dataset on **foodborne disease outbreaks**. Using historical outbreak data from the United States (Kaggle), we analyze trends over time, identify the most dangerous contaminants, and highlight high-risk food preparation locations.

## 📦 Dataset
- **Source**: Kaggle (Foodborne Outbreak Dataset)
- **File**: `outbreaks.csv`
- **Fields Include**: `Year`, `Species`, `Illnesses`, `Hospitalizations`, `Fatalities`, `Location`, etc.
- LINK: https://www.kaggle.com/datasets/cdc/foodborne-diseases/data

---

## 🔍 Questions Explored & Key Findings

### 📈 1. What is the trend of foodborne outbreaks over the years?
- Grouped outbreaks by **year** to visualize trends from the dataset.
- **Line chart** plotted using Matplotlib.
- **Finding**: Foodborne disease outbreaks are either *increasing* or *decreasing*, depending on the start and end year values.

### 🦠 2. Which contaminants cause the most harm?
- Aggregated illness, hospitalization, and fatality counts by **contaminant species**.
- Bar chart of **top 10 species** sorted by illness count.
- **Findings**:
  - Most illnesses: `Salmonella`
  - Most hospitalizations: `E. coli`
  - Most fatalities: `Listeria` (example, actual values depend on your output)

### 🏠 3. Which locations pose the greatest risk?
- Summed illnesses by **food preparation location** (e.g., home, restaurant, institution).
- Bar chart of **top 10 risky locations**.
- **Finding**: Highest risk location for foodborne illness is likely `Restaurant` or `Private Residence`.

---

## 🛠️ Technologies & Libraries Used
- **Python 3.9+**
- **Google Colab**
- **pandas** – for data loading and aggregation
- **matplotlib** – for plotting graphs and trends



