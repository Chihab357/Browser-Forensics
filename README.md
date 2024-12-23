# 🔍 Browser Forensics Report

This repository presents a **Browser Forensics Project**, focusing on analyzing browser data to extract meaningful insights for cybersecurity and forensic investigations. The project was conducted using **Browser History Examiner** to analyze data from **Mozilla Firefox** and **Microsoft Edge**.

![Soul Terry GIF](https://media1.tenor.com/m/BU5LjuSJCV4AAAAd/soul-terry.gif)

---

## 🚀 **Project Objectives**
- Extract and analyze browsing histories from Edge and Firefox.
- Identify and compare online behavior, including:
  - Websites visited.
  - Search terms used.
  - Bookmarks and saved credentials.
- Highlight key forensic artifacts like cookies, downloads, and session data.

---

## ⚙️ **Tools & Technologies**
- **Browser History Examiner**: Used for data extraction and analysis.
- **SQLite**: Format for browser history databases.
- **Browsers analyzed**: Mozilla Firefox & Microsoft Edge.

---

## 📂 **Project Workflow**
1. **Data Extraction** 🛠️  
   - Browser history files were securely extracted from the operating system.  
   - Tools like Browser History Examiner imported and parsed the data.

2. **Data Analysis** 🔍  
   - Extracted data included:
     - URLs of visited sites.
     - Timestamps and frequency of visits.
     - Cached files and images.
     - Saved login credentials and search terms.

3. **Data Comparison** 📊  
   - Mozilla Firefox and Microsoft Edge were compared based on:
     - Volume of data stored.
     - Types of sites visited.

4. **Reporting** 📝  
   - Exported detailed reports in **PDF** and **HTML** formats for further analysis and documentation.

---

## 🎯 **Key Findings**
- **Edge** contained more detailed browsing activity compared to Firefox.  
- Retrieved sensitive data included:
  - **Bookmarks:** 21 in Edge, 4 in Firefox.
  - **Logins and passwords:** Hostnames, dates created, and usage counts.
  - **Cached files and images:** Content types and sizes.

---
