# 📊 Financial Statement Data Cleaning Project

## 🔍 Overview

This project focuses on cleaning and transforming messy financial statement data into a structured, analysis-ready format.

The dataset contains **Profit & Loss (P&L)** and **Balance Sheet** information, which were originally unorganized and required significant preprocessing before analysis.

---

## ⚠️ Problem Statement

The raw dataset had several issues:

* Mixed headers and data in the same column
* Presence of null and blank rows
* Financial sections (P&L and Balance Sheet) combined
* Year values spread across multiple columns
* Metadata rows such as *"in million USD"*
* Inconsistent column structure

---

## 🛠️ Tools Used

* Microsoft Excel
* Power Query

---

## 🧹 Data Cleaning Steps

1. Loaded raw dataset into Power Query
2. Identified and labeled financial sections (P&L and Balance Sheet)
3. Created a **Statement Type** column
4. Applied **Fill Down** to assign correct categories
5. Removed null rows and unnecessary metadata
6. Corrected column misalignment issues
7. Renamed columns for clarity
8. Unpivoted year columns into a single column
9. Converted fiscal year format (e.g., *FY '09*) into standard year format (2009)
10. Set appropriate data types for all columns

---

## 📊 Final Output Structure

The cleaned dataset is structured as follows:

| Statement Type | Account | Year | Amount |
| -------------- | ------- | ---- | ------ |
| P&L            | Revenue | 2009 | 30990  |
| Balance Sheet  | Cash    | 2009 | 7021   |

---

## 💡 Key Learnings

* Handling real-world messy financial data
* Using Power Query for data transformation
* Converting wide data into tidy (long) format
* Managing null values and inconsistent structures

---

## 📂 Project Structure

```
Financial-Statement-Data-Cleaning/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── screenshots/
│
└── README.md
```

---

## 🌐 Data Source

The dataset used in this project was obtained from:

👉 https://www.simfin.com/

SimFin provides financial statement data including Profit & Loss and Balance Sheet information.

---

## 🚀 Conclusion

This project demonstrates the process of converting unstructured financial data into a clean and usable format, which can be further used for analysis and visualization in tools like Power BI.

---
