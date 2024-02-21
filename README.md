# AdventureWorks Database:
[Installation and Configuration Guide](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms){:style="color: blue"}

![Description de l'image](https://github.com/GeoffroyMorel1992/Database-sample-AdventureWorks2017/raw/main/Lien%20-%20database%20AdventureWorks.png)


AdventureWorks is a widely used Microsoft sample database created to demonstrate and elucidate database design principles and implementations in SQL Server. The database comprises two main components:

- **Database 1 (AdventureWorks2017.bak): OLTP (Online Transaction Processing)**
  - Represents a bike component and sales company, AdventureWorks Cycles.
  - Focuses on capturing day-to-day operational data, including customer orders, sales invoices, product inventories, and purchase orders.
  - Optimized for fast data retrieval and manipulation needed for real-time transactions.

- **Database 2 (AdventureWorksDW2017.bak): Data Warehouse**
  - Provides an aggregated and historical view of the OLTP data, primarily intended for analytical tasks.
  - Stores pre-calculated facts and dimension tables for efficient data analysis and reporting.
  - Designed for faster querying and summarizing large datasets over extended periods.

# Database Diagrams
The diagrams available on the SQL server provide a comprehensive visual representation, showcasing the interconnections between all the tables.

# Limits of the Database
- **Limited scope:** Represents a fictitious company, not catering to specific industry needs.
- **Data size:** Not large enough for extensive data analysis and might not reflect the complexities of real datasets.
- **Static data:** Doesn't simulate real-time data updates or ongoing business activities.

# Alternative Solutions
- **Populate with real data:** Consider loading the database with industry-specific datasets for more realistic analysis.
- **Extend and customize:** Add tables, modify existing ones, and tailor the schema to fit your specific requirements.
- **Integrate with other data sources:** Combine AdventureWorks with other databases for broader insights.
- **Explore production-grade databases:** Choose databases designed for handling large-scale, security-critical applications.
