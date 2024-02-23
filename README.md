# AdventureWorks Database Introduction:
AdventureWorks is a widely used Microsoft sample database created to demonstrate and elucidate database design principles and implementations in SQL Server.

The fictional company AdventureWorks manufactures, sells and resells bicycles, accessories and cycling apparel internationally.

# AdventureWorks Database structure:
<a href="https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms" style="color: blue;">Installation and Configuration Guide</a>

![Description de l'image](https://github.com/GeoffroyMorel1992/Database-sample-AdventureWorks2017/raw/main/Lien%20-%20database%20AdventureWorks.png)

 The database comprises two main components:

- **Database 1 (AdventureWorks2017.bak): OLTP (Online Transaction Processing)**
    - Focuses on capturing day-to-day operational data

- **Database 2 (AdventureWorksDW2017.bak): Data Warehouse**
  - Provides an aggregated and historical view of the OLTP data, primarily intended for analytical tasks and data analysis
 
![Description de l'image](https://github.com/GeoffroyMorel1992/Database-sample-AdventureWorks2017/blob/main/Data%20process%20%20OLTP%20-%20OLAP.png)

# Database Diagrams
The diagrams available on the SQL server provide a comprehensive visual representation, showcasing the interconnections between all the tables.

# Limits of the Database
- **Data size:** Not large enough for extensive data analysis and might not reflect the complexities of real datasets.
- **Static data:** Doesn't simulate real-time data updates or ongoing business activities.

# Alternative Solutions
- **Extend and customize:** Add tables, modify existing ones, and tailor the schema to fit your specific requirements.

