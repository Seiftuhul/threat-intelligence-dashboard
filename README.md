<<<<<<< HEAD
# threat-intelligence-dashboard
Phishing URL data analysis and visualization dashboard using Python.
=======
# Threat Intelligence Dashboard

**Analyst:** Seif Tuhul  
**Date:** August 10, 2025

---

## Overview

This project downloads phishing URL data from PhishTank, analyzes it using Python libraries (`requests`, `pandas`, `matplotlib`), and visualizes the top phishing domains in a bar chart. It demonstrates basic threat intelligence gathering and data visualization skills to identify common phishing sources.

---

## Tools Used

- Python 3.x  
- Requests (for data download)  
- Pandas (for data manipulation)  
- Matplotlib (for charting)

---

## Data Source

Phishing URL data was downloaded from PhishTank’s publicly available CSV dataset containing verified active phishing URLs.

---

## Analysis

- Parsed the CSV to extract domain names from URLs.  
- Counted the frequency of phishing reports per domain.  
- Identified the top 10 domains with the highest number of phishing reports.

---

## Visualization

The included bar chart displays the top 10 reported phishing domains based on the analyzed PhishTank dataset.

---

## Findings

The visualization highlights the most commonly reported phishing domains, helping security analysts focus on blocking or monitoring these domains.

---

## Recommendations

- Monitor and block the identified high-risk phishing domains at network perimeters.  
- Update phishing awareness training using real-world examples from the dataset.  
- Schedule regular updates of phishing data and refresh the dashboard for ongoing threat monitoring.

---

## Attachments

- Dashboard Python Script  
- Phishing URL CSV Data  
- Screenshot of chart image: `screenshots/top_phishing_domains_20250810_040524.png`

---

## Skills Demonstrated

- Threat intelligence data collection  
- Data analysis using pandas  
- Data visualization with matplotlib  
- Python automation scripting

---

Feel free to review the attached files and customize the dashboard for deeper analysis.
>>>>>>> bae51c8 (Initial commit with dashboard.py, report, screenshots, README, ignoring data folder)
