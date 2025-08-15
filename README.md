🌍 *****Global Earthquake Tracker*****

📌 ***Project Description***
This end-to-end data analytics project leverages Microsoft Fabric to monitor and analyze global earthquake events in near real-time. Using public seismic datasets, it captures, processes, and visualizes earthquake activity to aid disaster preparedness and decision-making.

The solution spans the full data lifecycle — from data extraction and transformation to warehouse storage and interactive reporting.

🔹 ***Process Overview***

📥 *Data Extraction* – Pull earthquake event data from global seismic activity APIs and public datasets.

🔗 *Data Integration* – Combine multiple feeds containing magnitude, location, depth, and time data.

🧹 *Data Cleaning & Transformation* – Standardize formats, handle missing values, and enrich with regional/geospatial context using Python & Spark.

📊 *Data Analysis* – Identify trends in earthquake frequency, intensity distribution, and regional impact.

📈 *Data Visualization* – Deliver interactive Power BI dashboards for global earthquake monitoring.


🏗 ***Solution Architecture***

An integrated pipeline from data ingestion to insightful reporting.

![Solution Architecture](https://github.com/naveen12334/Global-Earthquake-Tracker/blob/main/Solution%20Architecture/Architecture.png)

🗄 ***Data Source***

💾 *Website Feeds* – Global earthquake data sourced from public APIs and online datasets.

*Website Link* - ![Website Link](https://earthquake.usgs.gov/fdsnws/event/1/#parameters)


📥 ***Lakehouse*** – Central storage for raw earthquake event logs before transformation.

![Lakehouse](https://github.com/naveen12334/Global-Earthquake-Tracker/blob/main/Data%20Lakehouse/Data%20Ingestion.png)


📥 ***Data Extraction***

⚙ *Python & Spark* – Automated scripts to extract and store seismic data in the Lakehouse.

![Data Extraction](https://github.com/naveen12334/Global-Earthquake-Tracker/blob/main/Pyspark%20Notebooks/Data%20Extraction/Data%20Extraction.png)


🔄 ***Data Transformation***

🛠 *Python & Spark* – Clean, enrich, and standardize earthquake data for analytical use.

![Data Transformation](https://github.com/naveen12334/Global-Earthquake-Tracker/blob/main/Pyspark%20Notebooks/Data%20Transformation/Data%20Transformation.ipynb)


🏭 ***Data Loading***

🛠 *Python & Spark* – Data Loading in Warehouse.

![Data Loading](https://github.com/naveen12334/Global-Earthquake-Tracker/blob/main/Pyspark%20Notebooks/Data%20Ingestion/Data%20Ingestion.png)

📦 *Warehouse* – Stores processed datasets ready for analysis.

![Data Ingestion](https://github.com/naveen12334/Global-Earthquake-Tracker/blob/main/Data%20Warehouse/Production%20data.png)


🔀 ***Data Pipeline Orchestration***

🗓 *Data Factory* – Schedules and manages data pipeline execution for continuous updates.

![Data Pipeline](https://github.com/naveen12334/Global-Earthquake-Tracker/blob/main/Data%20Pipeline/ETL%20Pipeline.png)


![Pipeline Scheduling](https://github.com/naveen12334/Global-Earthquake-Tracker/blob/main/Data%20Pipeline/Pipeline%20Scheduling.png)


📊 ***Power BI Dashboard***

![Power BI](https://github.com/naveen12334/Global-Earthquake-Tracker/blob/main/Power%20BI%20Report/PBI%20Dashboard.png)

Interactive visuals to track:

Recent earthquake events by location and magnitude

Frequency trends over time

Regional seismic risk levels


🚀 ***Business Value***

📍 Disaster Preparedness – Real-time monitoring to aid emergency response.

🌐 Global Awareness – Educates public and policymakers about seismic risks.

📊 Data-Driven Decisions – Supports research, insurance modeling, and infrastructure planning.

🛠 Automation – Minimizes manual intervention for continuous seismic tracking.
