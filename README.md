![Project Banner](assets/banner.png)

# 📊 Coders of Bangalore – Instagram Follower Intelligence

A **pure Python data analysis project** that reads raw Instagram follower data of OpenAI-related accounts and turns messy, unstructured text into clear, structured insights.  
The same parsing logic works seamlessly for **demo data and real-world collected data** without any code changes.

> **A real-world data parsing challenge: converting raw Instagram text into structured, actionable insights using pure Python.**

---

## 🧩 Project Story

During a visit to Bangalore, Sam Altman posed a time-bound data challenge instead of funding:

> Collect raw Instagram data of OpenAI followers and extract meaningful insights within 24 hours.

### The Task
From unstructured Instagram profile data, determine:
- The profile with the highest number of posts
- The profile with the highest number of followers
- The profile following the most accounts
- The set of profile categories and their respective counts

### The Objective
Build a **robust and reusable Python pipeline** that:
- Transforms raw text into structured data
- Handles real-world inconsistencies
- Produces accurate results using the same codebase for both demo and real datasets

This repository contains the **final, production-ready implementation** of that solution.


## 📂 Dataset Information

**Location:** `data/`

| File | Description |
|---|---|
| `demo_data.txt` | Sample dataset used while building parsing logic |
| `initial_data.txt` | Raw collected Instagram data |
| `final_data.txt` | Cleaned and finalized dataset |

**Data Format**
- Each Instagram profile is stored as a text block
- Profiles are separated by empty lines
- Fields include posts, followers, following, and category

---

## 🛠️ Tech Stack

- **Language:** Python 🐍
- **Tools:** Jupyter Notebook
- **Libraries:** Standard Python libraries (no heavy dependencies)

---

## 🔄 Project Workflow

1. **Data Collection**
   - Raw Instagram profile data collected manually

2. **Parsing**
   - Split raw text into profile chunks
   - Convert each chunk into a dictionary

3. **Validation**
   - Tested logic using demo data

4. **Final Analysis**
   - Same code executed on real-world dataset

5. **Insights**
   - Extracted maximums and category distributions

---

## 📊 Exploratory Data Analysis (EDA)

The notebook explores follower distribution and profile behavior before final conclusions.

**Follower Analysis Snapshot**
![EDA Followers](assets/eda_followers.png)

Key observations include:
- Large imbalance in follower counts
- A small number of profiles dominate reach

---

## 📈 Final Results & Insights

After running the pipeline on the final dataset, the project identifies:
- Profile with **maximum posts**
- Profile with **maximum followers**
- Profile with **maximum following**
- All unique profile categories
- Count of profiles in each category

**Results Overview**
![Results Summary](assets/results_summary.png)

---

## 📌 Key Insights

- Digital creators form the largest category
- High follower count does not always correlate with high posting frequency
- Some accounts follow many users but have relatively fewer followers
- Clean data structure makes analysis scalable and reusable

---

## ⚠️ Limitations

- Data collection is manual
- Private accounts are excluded
- Category labels depend on Instagram’s self-declared metadata

---

## 🚀 Future Improvements

- Automate data collection (where permitted)
- Store parsed data in a database
- Add time-based growth analysis
- Build an interactive dashboard

---

## 🗂️ Repository Structure

- **coders-of-bangalore/**
  - **assets/**
    - `banner.png` — Project banner for README
    - `eda_followers.png` — EDA visualization
    - `results_summary.png` — Final analysis summary
  - **data/**
    - `demo_data.txt` — Demo dataset used for logic testing
    - `initial_data.txt` — Raw collected Instagram data
    - `final_data.txt` — Cleaned and final dataset
  - `coders-of-bangalore.ipynb` — Main analysis notebook
  - `README.md` — Project documentation


---

## ▶️ How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/mdrayan001/coders-of-Bangalore.git
cd coders-of-Bangalore
```
### 2️⃣ Open the notebook
```bash
jupyter notebook coders-of-bangalore.ipynb
```
### 3️⃣ Run all cells

The notebook automatically loads data from the data/ folder and produces results.

👤 Author

MD Rayan
Data Science & AI Enthusiast

📧 Email: rayanmd641@gmail.com

🔗 Linkedin: [https://linkedin.com/mdrayan001](https://www.linkedin.com/in/mdrayan001/)

