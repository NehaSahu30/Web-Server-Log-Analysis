# 🌐 Calgary HTTP Log Analysis – Python Assessment

This project analyzes web server logs from the **University of Calgary Computer Science Department**, using the Calgary HTTP dataset. It demonstrates practical data handling, cleaning, and analysis skills using Python, with a focus on real-world log file structures and server behavior.

---

## 📁 Dataset Information

- **Source**: [Calgary HTTP Logs](https://ita.ee.lbl.gov/html/contrib/Calgary-HTTP.html)  
- **Format**: Apache Common Log Format  
- **Size**: ~5.4 MB (compressed), ~52 MB (uncompressed)  
- **Time Span**: ~1 year of server logs

---

## 🧠 Project Tasks

### 🔹 Part 1: Data Loading & Cleaning
- Handled `.gz` compressed files
- Parsed Apache log entries using regular expressions
- Converted timestamp to datetime format
- Cleaned invalid/missing entries
- Extracted and normalized fields for analysis

### 🔹 Part 2: Analysis Questions

| Question | Description |
|----------|-------------|
| Q1 | Total number of log records |
| Q2 | Count of unique hosts |
| Q3 | Unique filenames requested per day |
| Q4 | Total number of 404 responses |
| Q5 | Top 15 filenames causing 404 errors |
| Q6 | Top 15 file extensions for 404s |
| Q7 | Bandwidth usage per day in July 1995 |
| Q8 | Hourly request distribution |
| Q9 | Top 10 most requested filenames |
| Q10| HTTP response code distribution |

---

## 📦 Tools & Libraries
- Python 3
- Pandas
- Regular Expressions
- Matplotlib (optional for plots)
- Jupyter Notebook

---

## 📄 Files Included

- `analysis.ipynb` – Main notebook with code & outputs
- `analysis.html` – Exported HTML version of the notebook
- `transcript.txt` – Written version of the video walkthrough
- (Optional) `README.md` – This file

---

## 📹 Walkthrough Video
A short recorded video explaining the notebook and results is provided separately via YouTube (unlisted). Link shared via form.

---

## 🧠 Key Learning
This assessment demonstrates how to work with raw log data, clean and transform it using Python, and generate meaningful insights from semi-structured data in a reproducible format.

---
