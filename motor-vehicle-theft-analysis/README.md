

---

# 🚗 Motor Vehicle Theft Analysis – SQL Project

## 📑 Table of Contents

* [📌 Project Overview](#-project-overview)
* [📊 Dataset Structure](#-dataset-structure)
* [🔍 Analysis Objectives](#-analysis-objectives)
* [🛠 Methodology](#-methodology)
* [📋 Analytical Questions](#-analytical-questions)
* [🔗 Project Links](#-project-links)
* [🤝 Contributing](#-contributing)
* [📩 Support](#-support)
* [⭐ Support the Project](#-support-the-project)

---

## 📌 Project Overview

This project focuses on analyzing a Motor Vehicle Theft dataset using SQL to uncover hidden patterns, trends, and risk factors associated with stolen vehicles.

The analysis is designed to:

* Identify theft-prone regions
* Understand vehicle attributes most targeted by thieves
* Examine time-based theft patterns
* Evaluate differences between vehicle categories (Luxury vs Standard)

The insights generated aim to support better decision-making in areas such as crime prevention, security planning, and policy formulation.

---

## 📊 Dataset Structure

### 📁 1. stolen_vehicles

* `vehicle_id` – Unique vehicle identifier
* `vehicle_type` – Category (Saloon, SUV, Hatchback, etc.)
* `make_id` – Links to vehicle brand
* `model_year` – Year of manufacture
* `color` – Vehicle color
* `date_stolen` – Theft date
* `location_id` – Links to location data

### 📁 2. make_details

* `make_id` – Unique identifier
* `make_name` – Brand (Toyota, Ford, etc.)
* `make_type` – Classification (Luxury or Standard)

### 📁 3. locations

* `location_id` – Unique identifier
* `region` – Region name
* `country` – Country
* `population` – Total population
* `density` – Population density

---

## 🔍 Analysis Objectives

### 🚘 Vehicle Profiling

* Determine commonly targeted vehicle types and brands
* Analyze vehicle features such as color, age, and production year
* Examine theft distribution across luxury and standard vehicles

### 🌍 Geographic Insights

* Identify regions with high theft concentration
* Evaluate how population size and density influence theft rates
* Detect potential geographic hotspots

### 📆 Temporal Trends

* Track theft patterns over time (monthly and yearly)
* Identify peak periods of vehicle theft
* Explore seasonal variations

### ⚖️ Category Comparison

* Compare theft frequency across vehicle segments
* Highlight high-risk categories

---

## 🛠 Methodology

### 🔹 Data Preparation

* Imported CSV files into a SQL database
* Created structured tables
* Cleaned and validated the data

### 🔹 Data Processing

* Joined tables using foreign keys
* Derived new fields like:

  * Vehicle age
  * Month and year from date

### 🔹 Data Analysis

* Aggregated theft counts
* Identified patterns and trends
* Compared different categories

---

## 📋 Analytical Questions

### 🚘 Vehicle Insights

* What is the total number of stolen vehicles recorded?
* Which vehicle categories experience the highest theft frequency?
* Which brands are most frequently targeted?
* How does theft distribution vary by vehicle color?
* Which combinations of make and production year are most vulnerable?
* How are thefts distributed across luxury vs standard vehicle types?
* How many unique brands are affected?

### 🌍 Regional & Demographic Analysis

* How does vehicle theft vary across regions?
* Which countries record the highest theft cases?
* Which regions have the highest luxury vehicle theft?
* Is there a relationship between population density and theft volume?
* Which regions combine high population with high theft risk?

### 📆 Time & Trend Analysis

* How does theft vary by vehicle production year?
* Which months show peak theft activity?
* What trends are observed over the years?
* Are there seasonal theft patterns?

### ⚖️ Comparative & Metrics Analysis

* Are luxury vehicles stolen more than standard vehicles?
* What is the average age of stolen vehicles?
* What is the average population of high-theft regions?
* Which vehicle segments are most at risk?

---

## 🔗 Project Links

🔗 GitHub Repository:
[https://github.com/DIMEJI-HOT/motor-vehicle-theft-analysis](https:/DIMEJI-HOT/github.com//motor-vehicle-theft-analysis)

---

## 🤝 Contributing

* Fork the repository
* Make improvements
* Submit a pull request

---

## 📩 Support

**Testimony Hakeem**
Data Analyst | SQL Developer | BI Enthusiast

📧 Email: [testimonyoladimeji2007@gmail.com](mailto:testimonyoladimeji2007@gmail.com)
🔗 LinkedIn: [www.linkedin.com/in/testimony-hakeem-31a04938b](http://www.linkedin.com/in/testimony-hakeem-31a04938b)

---

---

## ⭐ Support the Project

👉 Please give it a ⭐ on GitHub

---

