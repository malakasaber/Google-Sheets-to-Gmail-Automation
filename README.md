# Google Sheets → Gmail Automation (via Make.com)

## 📌 Project Overview
This project demonstrates a simple automation scenario built using [Make.com](https://www.make.com/).  
The goal is to **send an automatic Gmail notification whenever a new row is added to a Google Sheet**.

This is my **first Make scenario**, and I documented the process here as part of my automation learning journey.

---

## ⚙️ Scenario Workflow
1. **Trigger:** Google Sheets → *Watch Rows*  
   - Watches for new rows added in a selected spreadsheet.  
   - Limit set to **1** (processes one row per run).  

2. **Action:** Gmail → *Send an Email*  
   - Sends an email to the specified recipient (in this case, my own Gmail).  
   - Subject line and body are dynamically filled with data from the new row.  

---

## 📂 Repository Contents
- **README.md** → Documentation of the project.  
- **Google Sheets link** → [👉 Open Sheet Here](https://docs.google.com/spreadsheets/d/1hQtGaBBBJWKwh6kfVmYt1pY_ejOcvRQ2v8bZpXuznBE/edit?gid=0#gid=0)  
- **report/** → PDF or markdown file with screenshots and explanation of each step.  
- **images/** → Screenshots of the scenario setup in Make (modules, mapping, execution logs).  

---

## 🚀 How to Reproduce
1. Create a free account on [Make.com](https://www.make.com/).  
2. Create a new scenario.  
3. Add:
   - Google Sheets module → *Watch Rows* (connect your sheet).  
   - Gmail module → *Send an Email* (connect your Gmail).  
4. Map your sheet’s columns into the email subject and body.  
5. Run once, test by adding a new row to your sheet.  
6. Turn scenario **ON** and schedule it.  

---

## 📸 Screenshots
Screenshots of the setup and results are available in the report.

---

## 🛠️ Tools Used
- **Make.com** – Workflow automation platform  
- **Google Sheets** – Data source (trigger)  
- **Gmail** – Email notification (action)  

---

## 📖 Learning Outcome
- Gained hands-on experience with **triggers and actions in Make**.  
- Learned how to **map fields dynamically** between apps.  
- Successfully automated a real-life task with **no coding required**.  
