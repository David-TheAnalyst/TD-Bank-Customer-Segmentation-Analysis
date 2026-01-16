# TD-Bank-Customer-Segmentation-Analysis

<div align="center">
  <img src="https://github.com/David-TheAnalyst/TD-Bank-Customer-Segmentation-Analysis/blob/main/2.%20Customer%20Segmentation%20DB.png" alt="Flowpal Sales Dashboard Additional View" width="1000" height="600">
</div>


## **Introduction**

**Objective of the Project**

The primary objective of this project is to conduct a comprehensive customer segmentation and lifecycle analysis for TD Bank within the Banking and Financial Services industry in order to provide a clear roadmap to move from stable today to sustainable tomorrow.

It evaluates customer demographics, professional profiles, income distribution, tenure, and generational composition to understand how effectively the bank is acquiring, retaining, and growing customer value over time.

Despite a healthy average customer income of $114.4K and a customer base concentrated in peak earning years (average age of 46), the dashboard reveals a sharp 51% collapse in customer acquisition between 2024 and 2025. This decline represents a material threat to long-term portfolio sustainability if not addressed immediately.

This leads to the core analytical question of the project:

Is TD Bank building a future-ready customer base, or is it slowly aging out its portfolio while losing momentum in new customer acquisition?

To answer this, the analysis investigates:

-	Whether TD Bank is successfully attracting the next generation of customers (Gen Z and Millennials).
-	How income, gender, and occupation influence high-net-worth customer concentration.
-	The health of the customer retention funnel across lifecycle stages.
-	Whether the customer portfolio is diversified enough to withstand economic shocks.
-	Where operational and relationship management efforts should be focused to maximize lifetime value.

This report is not just a descriptive segmentation exercise. It is a strategic diagnostic designed to guide executive, marketing, sales, and risk decisions that will determine whether TD Bank sustains growth beyond 2026.


## **Key Datasets and Methodologies:**

**Dataset Overview**

The analysis uses a consolidated customer dataset that captures demographic, professional, financial, and lifecycle attributes of TD Bank customers. Each record represents a unique customer and includes variables related to age, gender, occupation, income, tenure, region, and customer segment.

Methodologies

The analysis is built using Microsoft Excel with the following techniques:

-	Data cleaning and standardization using Power Query
-	Pivot Tables for aggregation by generation, income bracket, occupation, and segment
-	Calculated fields for tenure and lifecycle classification
-	Time-based analysis using Join Date
-	Interactive dashboard visuals to support executive decision-making



## **Story of Data:**

This dataset tells a clear story of customer lifecycle progression and professional growth within TD Bank.

It shows how customers enter the bank as New, evolve into Emerging, and eventually become Loyal or Legacy clients. It also reveals a strong relationship between occupation and income bracket, highlighting which professions drive high-value segments.


At the same time, the data exposes a growing imbalance:

-	Strong income levels

-	Weak tenure depth

-	Declining new customer acquisition

-	Underrepresentation of younger customers

Together, these signals suggest that while the bank has valuable customers today, its future pipeline may be at risk.


## **Data Splitting and Preprocessing:**

Data Preparation

Before analysis, the dataset was reviewed to ensure:

-	No duplicate customer records
- No missing critical demographic or financial fields
-	Consistent formatting of Join Date and income values

Feature Engineering

Additional analytical fields were created, including:

-	Customer tenure (derived from Join Date)
-	Generational classification (Gen Z, Millennial, Gen X, Boomer)
-	Income brackets (Low, Medium, High)
-	Lifecycle segmentation (New, Emerging, Loyal, Legacy)


These transformations enabled clear lifecycle and cohort analysis across time.

## **Pre-Analysis:**

Data Split

- Dependent variables: Customer Segment, Tenure, Income Bracket

- Independent variables: Gender, Age, Region, Occupation, Income, Join Date

Industry Context
•	Industry: Banking & Financial Services

Stakeholders
- Chief Executive Officer (CEO)
- Chief Financial Officer (CFO)
- Chief Marketing Officer (CMO)
-	Head of Sales / Relationship Management
-	Chief Operating Officer (COO)
-	Chief Risk Officer (CRO)

Value to the Industry: This analysis helps the bank:

- Improve customer lifetime value
-	Reduce churn risk
-	Strengthen next-generation acquisition
-	Protect assets under management
-	Allocate marketing and sales effort more effectively

## **In-Analysis:** 

**Key Observations**

1. Customer acquisition dropped sharply from 51 new customers in 2024 to 25 in 2025, representing a 51% decline and the most serious risk identified in the analysis.
 
2. The average customer is 46 years old, earns $114.4K annually, and has only 5 years of tenure, indicating high earning power but short relationship depth.

3. High-income customers are increasingly female, with women (81) outnumbering men (72), making professional women a key growth driver for the bank.

4. The customer base is dominated by Millennials (147) and Gen X (141), while Gen Z (86) remains significantly underrepresented.
 
5. Only 40% of customers are Loyal, while 60% remain in New, Emerging, or Legacy stages, signaling a fragile retention funnel.
 
6. Doctors (72) and Teachers (77) form the largest customer groups, creating a well-diversified and recession-resistant professional portfolio.
 

**Initial Insights:**

-	The bank attracts high-income customers but struggles to retain them long enough to maximize lifetime value.
-	Low Gen Z representation threatens the future customer pipeline and long-term sustainability.
-	A large share of customers remains in early or unstable lifecycle stages, increasing churn risk if engagement is not improved.


## **Post-Analysis and Insights**

Key Findings

-	Growth risk: The sharp acquisition drop in 2025 threatens long-term sustainability

-	Lifecycle imbalance: Too many customers remain New or Emerging despite high income

- Gender opportunity: High-earning professional women are a clear strategic priority

-	Generational gap: Gen Z is not being captured at the required scale

-	AUM risk: Retired customers (75) signal future asset outflow


## **Data Visualizations & Charts:**

 <div align="center">
  <img src="https://github.com/David-TheAnalyst/TD-Bank-Customer-Segmentation-Analysis/blob/main/2.%20Customer%20Segmentation%20DB.png" alt="Flowpal Sales Dashboard Additional View" width="800" height="500">
</div>
 
The Excel dashboard provides a single-page executive view of customer health and risk.
To interact with the live visualization, Click on the [Link](https://github.com/David-TheAnalyst/TD-Bank-Customer-Segmentation-Analysis/blob/main/3.%20Customers%20Segmentation%20Analysis.xlsx)

**Key Metrics Displayed**

-	Average Income: $114.4K
-	Average Age: 46 years
-	Average Tenure: 5 years
-	Customer Acquisition Trend (2015–2025)

Core Visuals

-	Customer acquisition trend by year
-	Income bracket distribution
-	Customer segments donut chart
-	Customers by generation
-	Occupation distribution
-	Gender split in high-income segment


## **Recommendations and Observations:**

Executive & Strategic (CEO / Board)

-	Immediately investigate the root cause of the 2025 acquisition collapse
- Reposition the high-net-worth strategy to prioritize professional women
-	Treat customer acquisition as a board-level KPI for 2026

Marketing & Acquisition (CMO)

-	Launch a low-barrier product for Gen Z professionals
-	Focus campaigns on Doctors, Teachers, and Engineers
-	Shift messaging toward early-career wealth building

Sales & Relationship Management (Head of Sales)

-	Introduce a structured First 90 Days Program for New and Emerging customers
-	Use peer-to-peer referrals within professional networks
-	Actively migrate Medium-income customers into High-income profiles

Operations & Risk (COO / CRO)

-	Use automation for Low-wealth customers to improve efficiency
-	Introduce Family Office and Trust services for Boomers
-	Improve wealth measurement beyond annual income

## **Conclusion:**

TD Bank has a valuable customer base with strong income levels and professional diversity. However, the sharp decline in customer acquisition, combined with weak tenure depth and underrepresentation of Gen Z, presents a serious long-term risk.

To succeed in 2026 and beyond, the bank must:

-	Fix the acquisition pipeline
-	Convert Emerging customers into Loyal clients
-	Retain high-income professional women
-	Secure intergenerational wealth transfer


## **References:**

-	TD Bank Customer Segmentation Dataset [Link](https://github.com/David-TheAnalyst/TD-Bank-Customer-Segmentation-Analysis/blob/main/1.%20customers_rawdata.csv)

- Microsoft Excel (Power Query, Pivot Tables, Calculated Fields)


<h3 align="left">Connect with me on Socials:</h3>
<p align="left">
<a href="https://linkedin.com/in/david-ojo-984557231/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="david ojo" height="30" width="40" /></a>
<a href="https://twitter.com/david_ojo_1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="david_ojo_1" height="30" width="40" /></a>
<a href="https://medium.com/@davidojo2214" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="@davidojo" height="30" width="40" /></a>
<a href="http://www.youtube.com/@DavidOjo-j3v" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="davidojo-j3v" height="30" width="40" /></a>
</p>


Thanks for stopping by!


