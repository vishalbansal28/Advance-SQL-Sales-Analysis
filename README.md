## Advance SQL Sales Analysis: Dive into Data and Drive Insights

This repository provides a hands-on project focused on data analysis and visualization using SQL and Power BI. We'll explore sales data from the AdventureWorks sample database to uncover valuable insights and create a comprehensive dashboard for business decision-making.

**Project Goals:**

* **Clean and Prepare Data:**  Employ T-SQL techniques to cleanse, transform, and extract relevant sales data from the AdventureWorksDW database.
* **Build a Data Model:**  Connect tables in Power BI to establish relationships and create a solid foundation for analysis.
* **Visualize Insights:**  Craft an interactive dashboard in Power BI showcasing key metrics, trends, and geographical breakdowns.

**Getting Started:**

1. **Prerequisites:**
   * **SQL Server:** Ensure you have SQL Server (SQL Express) installed and configured.
   * **Power BI Desktop:** Download and install the latest version of Power BI Desktop.
   * **AdventureWorks Data:** Obtain and restore the AdventureWorksDW and AdventureWorksLT databases. You can find instructions on [https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms).
   * **Update AdventureWorksDW data:** Run the SQL script [https://github.com/techtalkcorner/SampleDemoFiles/blob/master/Database/AdventureWorks/Update_AdventureWorksDW_Data.sql](https://github.com/techtalkcorner/SampleDemoFiles/blob/master/Database/AdventureWorks/Update_AdventureWorksDW_Data.sql) to enhance your data.

2. **Understanding the Data:**
   * Explore the AdventureWorksDW database and differentiate between FACT tables and DIMENSION tables.
   * Identify tables relevant to your business request and user stories.

3. **Data Cleaning and Transformation:**
   * Utilize T-SQL to perform the following operations:
     * Rename columns.
     * Combine columns using techniques like `CONCAT`.
     * Apply filtering using the `WHERE` clause.
     * Sort data with `ORDER BY`.
     * Use `LEFT JOIN` to combine related tables.
     * Implement conditional logic with the `CASE()` function.
     * Handle null values with `ISNULL()`.

4. **Power BI Dashboard Construction:**
   * **Import Data:** Load the prepared data from SQL Server into Power BI Desktop.
   * **Data Model:** Connect tables to establish relationships and create a logical model.
   * **Measures:** Define calculations using DAX to analyze data and provide insights.
   * **Visualization:**  Create a visually engaging dashboard using various chart types (pie charts, line charts, bar charts, maps, etc.) and custom visuals.
   * **Interactive Elements:**  Allow users to filter and drill down into data for detailed exploration.

**Project Resources:**

* **Power BI Dashboard File:** [https://github.com/vishalbansal28/Advance-SQL-Sales-Analysis/blob/main/Sales%20Report.pbix](https://github.com/vishalbansal28/Advance-SQL-Sales-Analysis/blob/main/Sales%20Report.pbix) (Download and open in Power BI Desktop for interactive exploration)
* **Dashboard Screenshot:** [https://github.com/vishalbansal28/Advance-SQL-Sales-Analysis/blob/main/Sales%20Report.pdf](https://github.com/vishalbansal28/Advance-SQL-Sales-Analysis/blob/main/Sales%20Report.pdf)


**Let's get started!**  Dive into the world of data analysis and explore the power of SQL and Power BI to uncover hidden insights and drive business success.
