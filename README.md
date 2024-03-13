# 🚴‍♂️ Divvy Database Analysis - MSc in DMDS (2023-24) 

## Project Description

### 🌐 Introduction

Welcome to our final group project for the MSc in Data Management and Decision Sciences program at EMLYON Business School. In this project, we dive into the 'Divvy' database, a dataset derived from a bicycle-sharing service in Chicago, IL, similar to Lyon's "Velo'v." The dataset comprises two tables: 'Trips,' containing data on all trips from 2018, and 'Stations,' providing information about each station.

### 📊 Data Source

The data has been made available by Motivate International Inc. under a specific license, and the full dataset can be found [here](https://divvy-tripdata.s3.amazonaws.com/index.html). For a visual representation of station locations, we've created a map using Google Maps, accessible [here](https://www.google.com/maps/d/edit?mid=1o8GHKNl2UdNlCEVGWqzjTWxOoyB-EEg&usp=sharing). More details about Divvy can be found [here](https://divvybikes.com/system-data).

### 🛠️ Project Structure and Objectives

**Part 1 - Database Exploration :**
- Explored the database and tables, considering data types, duplicates, and correctness.
- Identified the common key between 'Trips' and 'Stations' tables.

**Part 2 - Missing Stations Analysis :**
- Imagined a scenario where the 'Stations' table hasn't been updated since 2013.
- Determined unique stations in 'Trips' not present in 'Stations,' presenting results as a percentage.

**Part 3 - Age Distribution and Trip Duration Analysis :**

*Part 3.1*
- Extracted age from birth year in 'Trips' for 2018, computed average trip duration, and exported data for plotting in Excel.
- Explored the age distribution and discussed findings.

*Part 3.2*
- Modified the query to group trips into age bins, created a histogram, and compared it with the Part 3.1 plot.
- Discussed potential differences and their validity.

**Additional Analysis:**
- Investigated peak usage times for stations, considering variations by day of the week and hour of the day.

### 🚀 Usage and Replication

Explore the SQL scripts, replicate analyses, and contribute to further insights. Your comments and suggestions are encouraged. The project emphasizes clarity in SQL code and includes comments for transparency and understanding.

We invite you to delve into the details, replicate the analyses, and contribute to further insights. Your feedback is highly appreciated!

---

Feel free to adjust and modify the description based on your preferences and specific project details.

