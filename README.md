# 📊 Customer Support Ticket Triage System  
**Week‑1 Internship Project | Python + Google Colab + GitHub**

---

## 📝 Project Description  
This project replicates a real-world customer support workflow. It processes incoming support tickets, cleans and analyzes text, classifies each ticket into a predefined issue category, assigns a priority level, and calculates SLA-based due times. The final output includes a support manager report and a clean CSV export for operational use.

---

## 📂 Dataset  
- **Source**: Kaggle – Customer Support Ticket Dataset  
- **Main Text Column**: `Ticket Description`  
- **Date Column**: `Date of Purchase`

---

## ⚙️ Workflow Steps  
1. **Data Loading & Exploration**  
   - Import CSV into Colab  
   - Inspect rows, columns, and missing values  
   - Preview sample tickets  

2. **Text Cleaning**  
   - Convert messages to lowercase  
   - Remove special characters and extra spaces  

3. **Issue Classification**  
   - Rule-based tagging into categories:  
     `PAYMENT`, `LOGIN`, `DELIVERY`, `REFUND`, `BUG`, `GENERAL`

4. **Priority Assignment**  
   - Assign levels:  
     - `P0` → Critical  
     - `P1` → High  
     - `P2` → Medium  
     - `P3` → Low  
   - Automated keyword detection (`auto_priority`)

5. **SLA Calculation**  
   - Map each priority to SLA hours  
   - Compute `due_time` using `Date of Purchase` + SLA

6. **Reporting & Export**  
   - Generate summary report (Issue Type vs Priority)  
   - Export final annotated dataset as CSV

---

## 🧰 Tools & Libraries  
- **Python**  
- **Google Colab**  
- **Pandas**  
- **NumPy**  
- **GitHub**

---

## 🔗 Google Colab Notebook  
You can view and run the project directly in Google Colab here:  
[Open in Google Colab](https://colab.research.google.com/drive/1mcHFIBfEpuYTGt1K6RUgHtcYiZ-aPJNo?usp=sharing)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mcHFIBfEpuYTGt1K6RUgHtcYiZ-aPJNo?usp=sharing)

---

## 📈 Evaluation Criteria  
- GitHub setup & professionalism – 20%  
- Data cleaning & logic – 25%  
- Classification & priority assignment – 25%  
- SLA calculation & reporting – 20%  
- Code clarity & comments – 10%

---

## 📤 Submission Checklist  
- ✅ Colab notebook uploaded to GitHub  
- ✅ Final CSV output included  
- ✅ README updated with project details  
- ✅ Repository link and Colab link submitted  

---

## 👨‍💻 Author  
**Karthikeyan**  
Python Intern | Learning Data & AI  
Location: Palayankottai, Tamil Nadu, India  

---

## 🌟 Highlights  
- Clean, professional GitHub setup  
- Transparent rule-based logic  
- SLA-driven reporting for real-world relevance  
- Export-ready outputs for managers  

---
