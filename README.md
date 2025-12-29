# Global Bike Sales & Sentiment Analysis Dashboard

## Project Overview
This project is a comprehensive **Power BI Dashboard** designed to analyze bike sales performance across multiple regions (Europe, North America, Pacific). Unlike standard sales reports, this project integrates **Customer Sentiment Analysis** and **Manager Performance Tracking** against set targets.

The goal is to provide actionable insights into profitability, customer satisfaction, and regional performance.

## Dashboard Preview
 
<img width="100%"  alt="Screenshot (48)" src="https://github.com/user-attachments/assets/39c76094-82ad-48e6-8388-3ac7723b7e7d" />
<img width="100%"  alt="Screenshot (47)" src="https://github.com/user-attachments/assets/c84653a1-f6e2-4b59-ae95-9be84ad7816e" />
<img width="100%"  alt="Screenshot (46)" src="https://github.com/user-attachments/assets/51108446-3d30-4919-baea-2c58c70aa795" />


## Key Features
* **Sales Performance:** Detailed breakdown of Profit, Revenue, and Cost by Country, Age Group, and Product Category.
* **Target vs. Actual:** Tracking regional managers' performance against their defined financial targets.
* **Sentiment Analysis:** Analysis of customer feedback (Positive/Negative) with confidence scores to gauge brand perception.
* **Demographics:** Insights into customer age groups and gender distribution.

## Data Sources & Structure
The analysis is built upon a Star Schema data model using a single Excel workbook (**`bikes sales.xlsx`**) containing the following sheets:
1.  **Sales Details**: Transactional data (Date, Customer Demographics, Product, Financials).
2.  **Targets**: Strategic data linking managers to regions and sales targets.
3.  **Customer Feedback**: Qualitative data containing User IDs, Countries, and Sentiment Scores.

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
*Created by [abood / aboodsirt]*
