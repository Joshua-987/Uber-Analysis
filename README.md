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
  -  Built paramter tables for dynamic analysis
    - Created a dynamic measure to generate adaptive titles and enable seamless switching between key metrics, such as *Total Bookings* and *Total Trip Distance*, within visuals.
  - Used an advanced level of dax to output the locations off most frequent pickup and drop off points as well as furthest trip.
    - These measures required me to be able to locate correct location IDs within trip details and match them with the location table, even using an inactive relationship to do so.

### 3. Data model

<img src="https://github.com/Joshua-987/Uber-Analysis/blob/main/Data%20Model.JPG" alt="Data Model" width="1000"/>

### 4. Analytics Use Cases:
Artist Analysis: Analyze top-performing artists by counting their appearances in the playlist, and explore trends over time.
Album Analysis: Track the most popular albums and how often songs from each album appear in the playlist.
Song Popularity: Measure song popularity through attributes like the number of streams, artist performance, or song genre.
Time Series Analysis: Investigate trends in song popularity by analyzing data over different time periods (e.g., weekly, monthly).
