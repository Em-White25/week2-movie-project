---

```markdown
# 🎥 Movie Data Analysis Project

A data analysis project using movie data sourced from TMDB (The Movie Database). This project explores how movies have performed across several KPIs, uncovering trends related to budget, revenue, profit, and popularity.

---

## 📁 Contents

1. [Introduction](#introduction)  
2. [Methodology](#methodology)  
3. [Insights](#insights)  
4. [Conclusion](#conclusion)

---

## 📌 Introduction

This project is based on movie data retrieved from TMDB's API. The primary goal was to analyze key performance indicators (KPIs) and extract insights on how movies performed at the box office.

By transforming raw JSON data into a structured format, we explored various dimensions such as revenue, budgets, profits, and return on investment (ROI) to understand what makes a movie financially successful.

---

## 🛠️ Methodology

The project followed a step-by-step data analysis pipeline that included:

- **Data extraction** from TMDB’s API
- **Cleaning and transforming** raw JSON data
- **KPI computation** and deriving insights
- **Data visualization** for storytelling

### 🔧 Tools Used:
- Python  
- Jupyter Notebook  
- Git & GitHub  

### 📦 Libraries Used:
- `pandas`  
- `ast`  
- `requests`  
- `matplotlib`  
- `os`

---

### 📥 STEP 1: API Data Extraction

TMDB returns data in JSON format with nested structures. Using the `requests` library, movie data was fetched using a list of IDs. Data was saved to CSV format after light validation and inspection.

---

### 🧹 STEP 2: Data Cleaning and Preprocessing

The raw dataset required multiple transformations:
- Dropped irrelevant columns
- Parsed stringified JSON objects (e.g., cast, crew, genres)
- Extracted key details for analysis such as director names, genre tags, and actor lists

---

### 📊 STEP 3: KPI Performance and Analysis

KPIs were analyzed to evaluate each movie’s success from both a business and audience perspective:

#### 🎬 Top 3 Movies by Revenue
- **Avatar: Enter the World of Pandora**
- **Avengers: Endgame**
- **Titanic**

#### 💸 Top 3 Movies by Budget
- **Avengers: Age of Ultron** – \$365M  
- **Avengers: Endgame** – \$356M  
- **Avengers: Infinity War** – \$300M  

#### 🤑 Highest Profit Movies
- **Avatar** – \$2.6B  
- **Avengers: Endgame** – \$2.4B  
- **Titanic** – \$2B  

#### 📉 Lowest Performing (Profit)
- **Avengers: Age of Ultron**  
- **Incredibles 2**  
- **Beauty and the Beast**  

#### 📈 Best ROI (Return on Investment)
- **Avatar** – 12x  
- **Titanic** – 11x  
- **Jurassic World** – 11x  

#### 📉 Worst ROI
- **Avengers: Age of Ultron** – 3x  
- **Incredibles 2** – 6x  
- **The Lion King** – 6x  

#### 🗳️ Most Voted Movies
- **Avatar** – 32,119 votes  
- **The Avengers** – 31,000 votes  
- **Avengers: Infinity War** – 30,000 votes  

---

## ✅ Conclusion

This project provided valuable insights into the movie industry through the lens of data. We identified financially successful and underperforming films, recognized the power of franchises, and uncovered trends tied to audience engagement.

### 🔍 Franchises vs. Standalone Movies

- **Franchise Dominance**:  
  Franchises such as *Avengers*, *Avatar*, and *Jurassic World* consistently dominated in terms of both budget and revenue. These films benefited from existing fanbases, extended universes, and large-scale marketing, often leading to massive box office returns.

- **Budget vs. ROI**:  
  High budgets did not always correlate with high profits or ROI. For instance:
  - *Avengers: Age of Ultron* had one of the highest budgets (~$365M) but only a **3x ROI**, making it one of the least efficient in terms of returns.
  - In contrast, *Avatar* and *Titanic*—despite more modest budgets—achieved **12x and 11x ROIs**, respectively.

- **Standalone Successes**:  
  While fewer in number, some standalone movies—especially those with strong narratives or renowned directors—performed exceptionally well. *Titanic* is a prime example, combining emotional depth and cinematic quality with widespread appeal.

### 🔑 Key Takeaways:
- **Franchises tend to bring big budgets and big returns**, but may suffer from **lower efficiency** (ROI) due to high costs.
- **High budget ≠ high ROI**. Avengers: Age of Ultro proves that.
- **Standalones can still compete**, especially when backed by compelling storytelling or direction, like the the Titanic and Avatar.


---
```
