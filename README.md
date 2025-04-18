# **End-to-End Cricket Data Analytics Project**

## **Overview**
This project showcases a complete data analytics workflow, starting from **web scraping** cricket data using Python to transforming it with SQL and Pandas, and creating an interactive **Power BI dashboard**. It highlights advanced features like custom DAX measures, dynamic visuals, and actionable insights.



## **Project Workflow**

1. **Data Extraction**:
   - Extracted player performance data using Python's `BeautifulSoup` and `requests`.
   - Saved the raw data in CSV format for further processing.

2. **Data Transformation**:
   - **SQL**:
     - Cleaned raw data and removed duplicates.
     - Generated structured datasets using queries for deeper insights.
   - **Python**:
     - Used `pandas` for merging, filtering, and automating transformations.

3. **Data Visualization**:
   - Built a **Power BI dashboard** featuring:
     - Custom visuals and dynamic scatter plots.
     - Hover-over tooltips for added insights.
   - Created DAX measures like:
     ```DAX
     Custom Batting Order = 
     SWITCH(
         TRUE(),
         dim_player[Player Name] = "Jos Buttler", 1,
         dim_player[Player Name] = "Virat Kohli", 3,
         ...
     )
     ```

---

## **Key Features**
- **Web Scraping**: Extracted real-world cricket data efficiently.
- **SQL**: Cleaned and filtered data for enhanced usability.
- **Power BI**: Developed a dashboard with conditional formatting and tooltips.
- **DAX**: Implemented custom calculations for ranking and performance analysis.

---

## **Technologies Used**

| Technology | Purpose |
|------------|---------|
| **Python** | Web scraping and preprocessing. |
| **SQL**    | Data cleaning and transformation. |
| **Power BI** | Data visualization and reporting. |
| **DAX**    | Custom measures and calculated columns. |
| **Power Query** | Data integration in Power BI. |

---

## **Setup and Usage**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/cricket-data-analytics.git

---





---


---

## **Future Enhancements**
- Include bowling performance metrics for a more comprehensive analysis.
- Use predictive analytics and machine learning to forecast player performance trends.
- Automate the data refresh process for real-time updates in the dashboard.

---

## **Technologies Used**

| Technology     | Purpose                                     |
|----------------|---------------------------------------------|
| **Python**     | Web scraping and data preprocessing.        |
| **SQL**        | Data cleaning, filtering, and transformations. |
| **Power BI**   | Creating interactive dashboards and visuals. |
| **DAX**        | Advanced calculations for dynamic insights. |
| **Power Query**| Data integration and model transformation.  |

---

## **Acknowledgments**
- **Python Community**: For the open-source libraries used in web scraping and data analysis.
- **Power BI Community**: For tutorials and inspiration to create engaging dashboards.
- Open-source tools and cricket websites for providing the raw data.

---

## **License**
This project is licensed under the MIT License. Feel free to use and modify it as needed.

---

## **Contact**
For any queries or suggestions:
- Email: tishasingh152003@gmail.com



