# Uber-Analysis

<img src="https://github.com/Joshua-987/Uber-Analysis/blob/main/Visuals/Overview%20Dashboard.JPG" alt="Overview Dashboard" width="1000"/>


<img src="https://github.com/Joshua-987/Uber-Analysis/blob/main/Visuals/Time%20Analysis.JPG" alt="Time-Analysis Dashboard" width="1000"/>


<img src="https://github.com/Joshua-987/Uber-Analysis/blob/main/Visuals/Detail%20Analysis.JPG" alt="Details Dashboard" width="1000"/>

### Project Goal
Analyze and build reports around booking data, to provide KPI and performance reports, and to uncover deeper insights from the dataset.

### 1. Data Exploration
- Broke analysis down into overview analysis and time analysis.
- Identified key metrics and attributes for each analysis section:
Atrributes from trip details such as: Total bookings, Total Booking Value and Total Trip Distance

### 2. Data Preparation

- **In Power Query**
  - Added relationships between the *trip details* and *location table*. I also used a inactive relationship since drop off location ID and pickup location ID both needed the location table.
  - Created a column in power query that output whether the pickup time was day or night for analysis.
- **In Power BI**
  -  Created measures for each of the KPI's such as *avg trip distance* and stored them in folders for organisation.
  -  Built paramter tables for dynamic analysis - Created a dynamic measure to create dynamic titles and use to dynamically switch between different fields within visuals such as *Total bookings* and *Total Trip Distance*.

### 3. Data model

### 4. Logical Considerations While Building the Dashboard
