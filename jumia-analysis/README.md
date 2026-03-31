# Jumia Product Performance Dashboard

**Business Intelligence & Data Analysis Project**

---

## Project Overview

This project analyzes product performance on Jumia using Excel to understand how pricing, discounts, ratings, and customer reviews influence customer engagement and product success.

The project was approached from a Business Intelligence perspective, focusing on translating business questions into analytical insights and delivering them through an interactive dashboard.

It follows an end-to-end workflow:

**Raw Data → Cleaning & Enrichment → Analysis → Dashboard → Business Recommendations**

---

## Business Problem

Jumia operates in a highly competitive e-commerce environment where pricing strategies and customer perception directly impact performance.

**Key business questions addressed:**

- What factors drive customer engagement (reviews)?
- Are discounts effective in increasing engagement?
- Do higher-rated products perform better?
- Which products should be prioritized for promotion?
- Are there products that pose quality or reputational risks?

---

## Business Requirements

To support decision-making, the following requirements were defined:

### KPI Tracking
- Total number of products  
- Average rating  
- Average discount percentage  
- Total number of reviews  

### Performance Analysis
Identify top-performing products by:
- Rating (customer satisfaction)  
- Reviews (engagement)  
- Discount levels (pricing strategy)  

### Relationship Analysis
- Discount percentage vs customer engagement  
- Rating vs customer engagement  

### Segmentation
- Rating categories (Poor, Average, Excellent)  
- Discount categories (Low, Medium, High)  

### Dashboard Requirements
- Interactive filtering using slicers  
- Clear visual breakdown of performance  
- Business-friendly layout for stakeholders  

---

## Dataset Description

The dataset contains product-level information including:

- Product Name  
- Current Price (KSh)  
- Old Price (KSh)  
- Discount (%)  
- Number of Reviews (used as a proxy for engagement)  
- Customer Rating (used as a proxy for satisfaction)  

---

## Data Cleaning & Preparation

Data preprocessing was performed to ensure accuracy and analytical usability:

### Cleaning
- Converted price fields from text (e.g., KSh 1,500) to numeric values  
- Extracted numeric ratings from text (e.g., “4.5 out of 5”)  
- Handled missing values in rating and review columns  
- Converted negative review values to positive  
- Removed duplicate product entries  

### Data Enrichment
- Created Discount Amount (KSh)  
- Created Rating Category (Poor, Average, Excellent)  
- Created Discount Category (Low, Medium, High)  

*(Detailed process documented in project notes)*

---

## Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to uncover patterns and relationships:

- Distribution of products across rating and discount categories  
- Identification of top-performing products  
- Analysis of customer engagement using review counts  
- Trend analysis using scatter plots  
- Comparison of performance across pricing strategies  

---

## Dashboard Design & Features

The dashboard was built using Excel PivotTables, charts, and slicers.

### Key Sections

#### Overview (Executive KPIs)
- Total Products  
- Average Rating  
- Average Discount (%)  
- Total Reviews  

#### Product Performance
- Top products by rating  
- Top products by number of reviews  
- Top products by discount percentage  

#### Trend Analysis
- Discount vs Reviews  
- Rating vs Reviews  

#### Product Categories
- Distribution by rating category  
- Distribution by discount category  

---

## Interactivity

The dashboard includes slicers for:

- Rating Category  
- Discount Category  
- Price Range  

This enables users to dynamically filter data and explore specific segments, such as:

- High-discount products  
- High-rated products  
- Low-performing products  

---

## Key Insights

- Discounts show a weak positive relationship with customer engagement  
- Higher ratings do not consistently lead to more reviews  
- Some products with high discounts but low ratings indicate potential quality issues  
- Top-performing products combine:  
  - High ratings (customer satisfaction)  
  - Strong review counts (engagement)  
- Discounts alone are not a reliable driver of performance  

---

## Business Recommendations

Based on the analysis:

- Focus on product quality alongside pricing strategies  
- Promote products with high ratings and strong engagement  
- Investigate high-discount, low-rated products for quality or experience issues  
- Use customer feedback (ratings & reviews) to guide product improvements  
- Implement promotion rules to avoid featuring low-rated products

 ---

## Skills & Competencies Demonstrated
- Business Requirements Analysis
- Exploratory Data Analysis (EDA)
- Data Cleaning & Transformation
- Data Visualization & Dashboard Design
- KPI Development & Performance Analysis
- Analytical Thinking & Insight Generation
- Stakeholder-Oriented Reporting
