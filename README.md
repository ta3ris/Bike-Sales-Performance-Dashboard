# Global Bike Sales & Sentiment Analysis Dashboard

## Project Overview
This project is a comprehensive **Power BI Dashboard** designed to analyze bike sales performance across multiple regions (Europe, North America, Pacific). Unlike standard sales reports, this project integrates **Customer Sentiment Analysis** and **Manager Performance Tracking** against set targets.

The goal is to provide actionable insights into profitability, customer satisfaction, and regional performance.

## Dashboard Preview

<img width="100%" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/93667acf-e3d7-4a5a-af09-d05cb2f72c52" />
<img width="100%" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/a0295029-1670-4591-9846-e6eff5b87101" />
<img width="100%" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/8e26590b-99a4-44b5-a2b0-7251897a9f91" />
 

## Key Features
* **Sales Performance:** Detailed breakdown of Profit, Revenue, and Cost by Country, Age Group, and Product Category.
* **Target vs. Actual:** Tracking regional managers' performance against their defined financial targets.
* **Sentiment Analysis:** Analysis of customer feedback (Positive/Negative) with confidence scores to gauge brand perception.
* **Demographics:** Insights into customer age groups and gender distribution.

## Data Sources & Structure
The analysis is built upon a Star Schema data model using the following sources:
1.  **`bikes_sales_details_from_kaggle.csv`**: Transactional data (Date, Customer Demographics, Product, Financials).
2.  **`targets_and_manager.csv`**: Strategic data linking managers to regions and sales targets.
3.  **`custmer_feedback.csv`**: Qualitative data containing User IDs, Countries, and Sentiment Scores.

## Tools & Technologies
* **Power BI Desktop:** For data modeling, DAX calculations, and visualization.
* **Data Modeling:** Creating relationships between Sales, Targets, and Feedback tables.
* * **Excel/CSV:** Raw data storage.
* **DAX:** Used for calculating measures like Total Profit and Profit Margins. 

## How to Use
1.  Clone this repository or download the ZIP file.
2.  Open the `Report` folder.
3.  Launch `bikes sales visualize.pbix` using Microsoft Power BI Desktop.
4.  *(Optional)* If asked for data sources, point them to the `Data` folder included in this repo.

---
*Created by [abood / ta3ris]*
