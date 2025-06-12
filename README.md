---

# 📘 README — Attendance Tracker Project

## 🎯 Project Overview

This project is a functional and visually appealing **Attendance Tracker** designed for a **non-profit organization's workshop series**. It demonstrates advanced Excel features including **Copilot prompt engineering**, **data operations**, **automated lookups**, **conditional formatting**, and **data visualizations**—structured to help managers easily monitor attendance and compliance across various departments.

---

## 📁 Workbook Structure

| Sheet Name          | Purpose                                                                   |
| ------------------- | ------------------------------------------------------------------------- |
| `List1_ContactInfo` | Contains attendee names and contact details (email addresses).            |
| `List2_Department`  | Maps attendee names to departments and groups; includes legend mappings.  |
| `List3_Details`     | Daily attendance records with status ("Yes"/"No") and presence flag.      |
| `Summary`           | PivotTables and charts summarizing trends, attendance rate, and insights. |

---

## ✅ Key Features Implemented

### 🔧 **Workbook Setup & Formatting**

* Clean, consistent headers: `Name`, `Month`, `Contact`, `Group/Department`, `Total Days Present`, `Actual Days Present`, etc.
* Use of **Copilot** and **custom cell styles** for consistent formatting (font size, bold headers, background color).
* Workbook saved as both a working file and a reusable **template**.

### 🧮 **Formulas and Data Management**

* **VLOOKUP/XLOOKUP** used to:

  * Retrieve contact info from `List1_ContactInfo`.
  * Map departments/groups from `List2_Department`.
* **SUMIF** applied in `Actual Days Present` to count presence from `List3_Details`.

### 🎨 **Conditional Formatting**

* "Attendance Status" column colored by status:

  * **Green** for "Present"
  * **Red** for "Absent"
* "Actual Days Present" uses **data bars** for intuitive visualization.
* Distinctive color highlights for each **department group**.

### 📊 **Data Visualization**

* PivotTables answer key questions:

  * 📅 Which day had the highest/lowest attendance?
  * 👥 Who attended most or only once?
  * 📈 Attendance rates per group and individual.
* Charts included to:

  * Visualize total attendees per day.
  * Analyze departmental attendance rates.

### 📐 **Attendance Compliance Logic**

* Attendance % = `Actual Days Present / Total Days Present`.
* Compliance rules:

  * Groups A, B, C: ✅ ≥ 80%
  * Groups D, E: ✅ ≥ 40%
* Column “Attendance Requirement Met” evaluates each person against criteria.

---

## 🧪 Functionality Tests

* All calculated fields (VLOOKUP, SUMIF, Attendance %) were tested for correctness.
* Conditional formatting was reviewed for accuracy and visual clarity.
* All PivotTables and charts were refreshed with up-to-date data.

---

## 🌐 Hosting & Access

* The file can be hosted on:

  * **OneDrive/SharePoint** (recommended for real-time collaboration).
  * **Google Drive** (read-only or editable links).
  * Or delivered as a downloadable **Excel template** (.xltx format) for reuse.

---

## 💼 Use Cases

* Team attendance monitoring.
* Workshop, training, or conference participation analysis.
* Volunteer engagement tracking for NGOs.
* Adaptable for schools, corporate training, or events.

---

## 📌 Versioning & Credits

* **Version:** 1.0
* **Prepared by:** Daniel Yao Agblevor
* **Date:** May 25, 2025
* **Email:** \[[mcdanagb@gmail.com](mailto:mcdanagb@gmail.com)]

---