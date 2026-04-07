# Movie-Metadata-Analysis
End-to-end movie metadata analysis using Excel and Power BI, including data cleaning, transformation, and interactive dashboard creation with insights on movie performance and popularity.
# 🎬 Movie Metadata Analysis Project

---

## 📌 1. Project Overview

This project focuses on analyzing a **movie metadata dataset** using Microsoft Excel and Power BI. The main objective is to clean, transform, and visualize the dataset to extract meaningful insights related to movie performance, popularity, and financial success. The project demonstrates a complete data analysis workflow from preprocessing to interactive dashboard creation.

---

## 🛠️ 2. Tools Used

* Microsoft Excel (Data Cleaning & Preprocessing)
* Power BI (Data Visualization & Dashboard Creation)

---

## 📂 3. Dataset

* **Source:** Sample Data
* **Data Contains:**

  * Movie Title
  * Director Name
  * Actor Names (Actor 1, Actor 2, Actor 3)
  * Language
  * Country
  * Content Rating
  * Duration
  * Genre
  * IMDB Score
  * Gross Revenue
  * Budget
  * Facebook Likes (Actors, Director, Movie)
  * Number of Votes and Reviews
  * Plot Keywords
  * Aspect Ratio
  * Poster Face Count

---

## 🔄 4. Steps Followed

### ✅ Movie Metadata Project – Steps Completed

1. **Cleaned Column Headings**

   * Functions Used: PROPER + SUBSTITUTE
   * Standardized all column headings for consistency and readability.

2. **Converted Formulas to Values**

   * Tool Used: Paste Special → Values
   * Ensured stable dataset by removing formulas.

3. **Reordered Columns**

   * Important columns like Movie Title were prioritized.

4. **Cleaned Colour Column**

   * Used TRIM and filled blanks with “Colour”.

5. **Cleaned Director and Actor Name Columns**

   * Removed unwanted characters and replaced blanks with “Unknown”.

6. **Cleaned Movie Title Column**

   * Removed unnecessary characters and handled missing values.

7. **Handled Missing Values (Year & Facebook Likes)**

   * Used MEDIAN to fill missing values.

8. **Cleaned Language and Country Columns**

   * Filled missing values with most frequent entries (English, USA).

9. **Cleaned Content Rating Column**

   * Replaced missing values with “Unknown”.

10. **Cleaned Duration Column**

* Converted minutes into `hh:mm:ss` format and filled missing values using median.

11. **Verified Genre Column**

* No missing or inconsistent values found.

12. **Verified IMDB and Facebook Likes Columns**

* Data was already clean and consistent.

13. **Formatted Gross and Budget Columns**

* Converted to Dollar ($) format and handled missing values.

14. **Cleaned Plot Keywords Column**

* Filled missing values with “Unknown”.

15. **Cleaned Poster Face Number & Aspect Ratio**

* Used median to fill missing values.

16. **Activated Hyperlinks**

* Converted text links into clickable links using Ctrl + K.

17. **Removed Duplicates and Converted to Table**

* Ensured structured and clean dataset.

18. **Imported Data into Power BI**

19. **Created Dashboard Pages**

* Overview
* Artists and Popularity
* Movie Analysis

20. **Designed Overview Page**

* Displayed KPIs such as Total Movies, Gross Revenue, IMDB Score, Votes

21. **Added Key Visualizations**

* Top 10 Movies, Year Trends, Box Office Status

22. **Designed Artists and Popularity Page**

* Highlighted actor and director insights

23. **Created Movie Analysis Page**

24. **Used KPI Cards**

25. **Added Slicers for Filtering**

26. **Implemented Multiple Charts**

* Bar, Column, Line, Pie, Donut, Waterfall

27. **Applied Theme and Styling**

28. **Added Navigation Buttons**

---

## 📊 5. Key Insights

* Most movies are produced in **English language** and from **USA**, indicating dominance in the dataset.

* A small number of movies contribute to **very high gross revenue**, showing that earnings are concentrated among a few top performers.

* Movies classified as **Blockbusters generate the highest revenue**, while **Flop movies fail to recover their budget**, highlighting performance differences.

* Higher **IMDB scores are generally associated with better-performing movies**, suggesting audience ratings influence success.

* Certain actors and directors show **higher popularity based on Facebook likes**, indicating strong fan following and influence.

* Movie production has **increased over the years**, reflecting growth in the film industry.

* Some high-budget movies still perform poorly, indicating **financial risk and unpredictability** in the movie industry.

* **Top 10 movies contribute a major share of total revenue**, emphasizing the impact of blockbuster films.

---

## 📁 6. Files Included

## 📁 Files Included  

- [Movie_Metadata.csv -uncleaned.xlsx](./Movie_Metadata.csv%20-uncleaned.xlsx) → Original dataset file  
- [Movie_Metadata_Cleaned.xlsx](./Movie_Metadata_Cleaned.xlsx) → Cleaned dataset  
- [Movie_Metadata_Dashboard.pbix](./Movie_Metadata_Dashboard.pbix) → Power BI dashboard file  
- [Movie_Metadata_Dashboard_pdf.pdf](./Movie_Metadata_Dashboard_pdf.pdf) → Dashboard PDF version  
- [README.md](./README.md) → Project documentation  

---

## ✅ Conclusion

This project demonstrates the complete workflow of data cleaning, transformation, and visualization using Excel and Power BI, providing meaningful insights into movie performance and trends.
