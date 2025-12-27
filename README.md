# 📊 Customer Support Ticket Triage System  
**Week-1 Internship Project | Python + Google Colab + GitHub**

## 📝 Project Description  
This project simulates a real-world customer support workflow. It processes incoming support tickets, cleans and analyzes the text, classifies each ticket into a predefined issue category, assigns a priority level, and calculates SLA-based due times. The final output includes a support manager report and a clean CSV export for operational use.

## 📂 Dataset Details  
- **Source**: Kaggle Customer Support Ticket Dataset  
- **Main Text Column**: `Ticket Description`  
- **Date Column**: `Date of Purchase`

## ⚙️ Steps Performed  
1. **Data Loading & Exploration**  
   - Read CSV file  
   - Inspect rows, columns, and missing values  
   - Preview sample tickets  

2. **Text Cleaning**  
   - Convert messages to lowercase  
   - Remove special characters and extra spaces  

3. **Issue Classification**  
   - Rule-based tagging into categories:  
     `PAYMENT`, `LOGIN`, `DELIVERY`, `REFUND`, `BUG`, `GENERAL`

4. **Priority Assignment**  
   - Assign priority levels:  
     `P0` (Critical), `P1` (High), `P2` (Medium), `P3` (Low)  
   - Logic based on keyword detection (`auto_priority`)

5. **SLA Calculation**  
   - Map each priority to SLA hours  
   - Calculate `due_time` using `Date of Purchase` + SLA

6. **Reporting & Export**  
   - Generate summary report: Issue Type vs Priority  
   - Export final annotated dataset as CSV

## 🧰 Tools & Libraries Used  
- **Python**  
- **Google Colab**  
- **Pandas**  
- **NumPy**  
- **GitHub**

## 📤 Submission Checklist  
- ✅ Colab notebook uploaded to GitHub  
- ✅ Final CSV output included  
- ✅ README updated with project details  
- ✅ Repository link and Colab link submitted

## 📌 Notes  
- All logic is rule-based and transparent  
- Project emphasizes clarity, reproducibility, and real-world relevance  
- No external libraries beyond Pandas and NumPy


