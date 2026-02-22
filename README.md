**UNIFIED MILITARY ANALYTICS AND COMPARISON DASHBOARD**

The Unified Military Analytics and Comparison Dashboard is a comprehensive data analytics project designed to analyze and compare global military power across 140+ countries.
The system integrates collecting data from GlobalFirepower.com, data engineering, KPI feature development, and interactive dashboard visualization into a unified analytics ecosystem.

The platform enables users to: 

•	Analyze global military rankings

•	Compare two countries side-by-side

•	Simulate coalition strength

•	Evaluate modernization levels

•	Assess defense spending intensity

**Project Architecture:**

Web Scrapping -> Data Cleaning -> KPI Engineering -> Dashboard Development -> QA and Final Documentation Submission.

**Data Source:**

Data was scraped from GlobalFirepower.com, especially from the following:

•	Military Strength Ranking: https://www.globalfirepower.com/countries-listing.php

•	Various metric-specific pages (e.g., Total Population, Total Military Personnel, Defense Budget, etc.) 

**Milestone 1 – Data Collection and Preparation**

**Objective:**

Build a reliable dataset from raw web data.

**Task Completed:**

•	Scraped 140+ country military profiles from GlobalFirepower.com

•	Extracted 50+ military indicators

•	Parsed ranking, manpower, assets, and budget metrics

•	Cleaned and standardized numerical values

•	Handled missing data

•	Converted text metrics into numeric format

Tools Used:

•	Python

•	Requests

•	BeautifulSoup

•	Pandas

•	NumPy

**Milestone 2 – KPI Engineering and Dashboard Preparation**

**Objective:**

Transform raw metrics into analytical KPIs.

**Engineered KPIs:**

Total Aircrafts:
To measure air power, all the aircrafts types were summed up -It is performed to find out the air strength of the country

Total Ground Power: 
To measure ground strength, tanks, armored vehicles and artillery is combined. -Represents the land warfare capability.

Overall Military Assets:
Combined indicator for total military strength.

Air to Ground Ratio:
This KPI shows whether a country is air dominant or ground dominant.

Military Ranks:
Countries were ranked based on the overall military assets using dense ranking.

Artillary Modernization:
To analyze modernisation the ratio of self propelled artillary to the total artillary is calculated.

Power Index Rank Gap:
Ranking in consistency using rank gap.

The Dashboard is prepared using the final files containing KPIs:

**Kpi overview:**

Provides the high level summary of global military strength.

•	Country Slicer

•	Total Ground Power 

•	Artillary Modernization 

•	Total Aircrafts

•	Average Military Rank

•	Ground Power Share


•	Total Assets

•	Total Assets Chart

•	Ground Power Share (Donut Chart)

**Power comparison:**

Compares air and the ground strength across countries   

•	Country Slicer

•	Total Ground Power

•	Total Aircraft

•	Air to Ground Ratio (Line Chart) 

**Modernization and ranking:**

Focuses on Modernization and Ranking Consistency.

•	Power index rank gap

•	Artillery Modernization

•	Country Slicer

**Milestone 3 – Dashboard Development**

Four interconnected dashboards were developed:

**Quick stats and Nation Overview Dashboards-**

**Objective:**

Provide a global snapshot of military strength rankings and trends.

Featured:

-Top 5 countries by Defense Budget

-Top 5 coutries by Military Assets

-Top 5 countries by Purchasing Power Parity

-Top 5 countries by air, Naval and Land Fleet

-Power index Rank KPI Card

**Nation Overview Dashboard-**

**Objective:**

Provide detailed country-level military profile.

Features:

-Country selector

-Power Index Rank KPI Card

-Military Force Composition consisting of tanks, Aircraft and Naval

-Manpower Composition consisting of Active Personnel, Paramilitary and Reserve Personnel

-Assets Per Million Population

**Compare Powers:**

**Objective:**

Allow side-by-side comparison between any two countries.

Features:

-Dual Country Selection

-Side-by-side KPI Comparison

-Rank Gap Analysis

-Asset Category Comparison

-Budget and Manpower Comparison

**Coalition Builder-**

**Objective:** 

Simulate alliance strength through multi-country aggregation.

Features:

-Coalition VS Reference Country Comparison

-Structural Composition Analysis

-Automatic Recalculation of:

•	Total Assets

•	Personnel

•	Defense Budget

Visualization Techniques Used:

•	KPI Cards

•	Clustered Bar Charts

•	Donut charts

**Milestone 4 – Testing, QA & Deployment**

Validation Performed

•	KPI accuracy cross-check

•	Filter & slicer testing

•	Parameter validation

•	Navigation flow verification

•	Layout standardization

•	Data aggregation checks

**Final Deliverables**

•	Fully integrated dashboard workbook

•	Structured GitHub repository

•	Complete documentation

•	Portfolio-ready analytics system

**How to use:**

1.	Open the dashboard file in Power BI Desktop/ Power BI Service

2.	Navigate using navigation buttons on the top.

3.	Apply filters.

4.	Compare countries or simulate coalitions.
