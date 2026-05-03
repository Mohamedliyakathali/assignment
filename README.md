# assignment
# 📊 Job Market Skill Analyzer (Python Project)

## 📌 Overview

This project is a **Job Market Skill Analyzer** built using Python. It simulates job listings and performs data analysis to identify **in-demand skills**, **job trends**, and **basic statistics**.

It demonstrates core **data analytics concepts** such as data cleaning, skill extraction, frequency analysis, and file handling.

---

## 🚀 Features

* 📄 Display job listings
* ➕ Add new job postings dynamically
* 🧹 Clean and normalize skill data
* 📊 Analyze top in-demand skills
* 📈 Generate basic job statistics
* 🔎 Search jobs by specific skills
* ⚡ Filter roles based on common skills
* 📦 Extract unique skills
* 💾 Export results to CSV and text files

---

## 🛠️ Technologies Used

* Python
* Core Python Libraries (No external libraries required)

---

## 📂 Project Structure

```
job-market-analyzer/
│
├── main.py              # Main Python script
├── job_skills.csv       # Generated dataset file
├── top_skills.txt       # Top skills output
└── README.md            # Project documentation
```

---

## 📊 Sample Dataset

The project uses a dictionary-based dataset:

* Job ID
* Role
* Company
* Skills

Example:

```
Data Analyst | ABC Corp | Excel SQL Python
Data Scientist | XyZ Ltd | Python ML Statistics
```

---

## ⚙️ How It Works

### 1️⃣ Job Listings

Displays all available job postings in a structured format.

### 2️⃣ Add Jobs

User can input new job roles, companies, and skills.

### 3️⃣ Data Cleaning

* Converts skills to lowercase
* Removes commas and extra spaces

### 4️⃣ Skill Analysis

* Extracts individual skills
* Counts frequency of each skill
* Displays top 5 most in-demand skills

### 5️⃣ Statistics

* Total number of jobs
* Number of unique skills
* Jobs requiring Python

### 6️⃣ Job Search

Search jobs based on a specific skill (e.g., SQL, Python).

### 7️⃣ Filtering

Identifies roles with commonly occurring skills.

### 8️⃣ File Export

* Saves job data into a `.csv` file
* Saves top skills into a `.txt` file

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```
git clone https://github.com/your-username/job-market-analyzer.git
cd job-market-analyzer
```

### Step 2: Run the Script

```
python main.py
```

---

## 📌 Example Output

```
Top skills by frequency:
python: 4
sql: 3
excel: 2
```

---

## 📈 Future Improvements

* Use **Pandas** for better data handling
* Add **data visualization (Matplotlib / Seaborn)**
* Build a **web app using Streamlit**
* Integrate with **real-world datasets (Kaggle)**
* Store data using **SQL database**

---

## 🎯 Learning Outcomes

* Python data structures (list, dictionary, set)
* Data cleaning and preprocessing
* Frequency analysis
* File handling in Python
* Basic data analytics workflow

---

## 👨‍💻 Author

**Mohamed Liyakath Ali**
B.Tech Artificial Intelligence & Data Science

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
