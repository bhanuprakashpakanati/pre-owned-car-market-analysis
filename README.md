# Pre-Owned Car Market Analysis

## Project Overview
This project involves a deep-dive analysis of the Indian pre-owned car market, specifically focusing on Maruti Suzuki vehicles. The goal was to transform raw listing data into actionable business intelligence to help optimize pricing, inventory management, and marketing strategies.

The analysis answers key business questions related to car depreciation, geographic demand, customer engagement, and the impact of vehicle specifications on sale price and popularity.

## Business Objectives
The analysis was guided by the following client objectives:
- **Increase Sales Conversion:** Identify features that make a car sell faster and for a better price.
- **Optimize Pricing Strategy:** Understand the key factors that determine a car's optimal selling price.
- **Improve Inventory Management:** Identify high-demand models and variants in specific regions.
- **Enhance Marketing Effectiveness:** Understand what drives customer engagement on listings.
- **Regional Strategy Development:** Tailor sales strategies based on geographic performance.

## Data Source
The primary dataset is `Car.csv`, which contains detailed listings for pre-owned Maruti Suzuki vehicles, including:
- Vehicle Specifications (Model, Year, Fuel Type, Kilometers Run)
- Pricing Information (Sale Price, Original Price)
- Geographic Data (City, Registered State)
- Listing Performance Metrics (Times Viewed, Is_Hot, Assured_Buy)

## Analysis & Key Findings
The SQL script (`SQL.sql`) contains queries structured around four main analytical themes:

### 1. Pricing & Valuation Analysis
- Calculated average depreciation rates for models like Wagon R, Swift, and Alto K10 over time.
- Analyzed the impact of kilometers driven, manufacturing year, fuel type, and city on the sale price.
- Built a foundational model to predict fair market value based on key attributes.

### 2. Geographic & Demographic Analysis
- Identified cities with the highest listing volumes and average prices.
- Mapped model popularity by city and state, revealing regional preferences.
- Discovered significant price variations for the same model across different cities.

### 3. Customer Engagement & Sales Performance
- Investigated which features (Transmission, Fuel Type, Assured Buy) lead to higher ad views.
- Evaluated whether "Hot" or "Assured Buy" listings command a price premium and attract more views.

### 4. Vehicle Specification Analysis
- Determined market share of different fuel types and transmission types.
- Assessed how the number of previous owners affects the sale price.
- Analyzed the price impact of having a warranty or fitness certificate.

## Repository Structure
pre-owned-car-market-analysis/
│
├── SQL.sql # Main SQL script containing all analysis queries
├── Client Requirement Document.docx
└── README.md # Project documentation (this file)


## Tools & Technologies
- **SQL:** For data extraction, transformation, and analysis.
- **Microsoft SQL Server:** Assumed database environment.

## How to Use
1.  Ensure your dataset is loaded into a SQL Server database table named `CAR`.
2.  Open the `SQL.sql` file in your preferred SQL client (e.g., SQL Server Management Studio).
3.  Execute the queries sequentially to replicate the analysis. Each section is clearly commented according to the business questions from the requirement document.

## Conclusion
This project successfully leverages SQL to extract meaningful patterns from a used car dataset. The insights generated can directly inform strategic decisions related to pricing, inventory stocking, and targeted marketing campaigns, ultimately providing a competitive edge in the dynamic pre-owned car market.
