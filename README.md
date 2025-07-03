# Case Study 1: Amazon-Product-Review-Analysis

## Author
**Adeniji Elijah Adetomiwa**
(**Junior Data Analyst**)

## Submission Date
July 2025


----

## Project Description

This case study is Key deliverable as part of my final lap in the *Digital SkillUp Africa* (DSA) Data Analysis Course, It showcase my learned ability Working as a Junior Data Analyst at RetailTech Insights, a company that provides e-commerce analytics solutions to sellers on platforms like Amazon. My team has been tasked with analysing product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

### DataSet Description
The dataset contains information scraped from Amazon product pages, including:
- Product details: name, category, price, discount, and ratings
- Customer engagement: user reviews, titles, and content
- Each row represents a unique product, with aggregated reviewer data
stored as comma-separated values
Total Records: 1,465 rows
TotalFields: 16 columns   [Download the Excel File](https://github.com/DataGuy-Eterniti/Amazon-Product-Review-Analysis/blob/main/Amazon%20case%20study.xlsx)

## Analysis Tasks and Key Business Operations (Exploratory Data Analysis)

1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs. the discounted price by category?
6. Which products have the highest number of reviews?

## Tools Used

- Microsoft Excel (Pivot Tables, Formulas, Charts) [Download Excel for Desktop](https://www.microsoft.com/en-us/microsoft-365/excel)
- Visualizations: Column Charts, Bar Charts, Pie Charts.

## Workflow & Methodology

The following process is the skeletal dreakdown of the pathway for the Analysis

### 1. Data Extraction and Cleaning
- The Dataset was loaded to Microsoft Excel and the key columns was identified for perfect understanding of the framework of the dataset, after which the data cleaning commenced using ower Query in Excel where duplicate records were removed, proper formatting was applied to each columns, additional calculated colmns were also created. [Cleaned DataSET](https://github.com/DataGuy-Eterniti/Amazon-Product-Review-Analysis/blob/main/Amazon%20Cleaned%20DataSet.png)

### 2. Pivot Tables
-I Built multiple pivot tables to answer key business questions: Average discount per category, Product count per category, Total reviews and average ratings by product, Price comparisons and some other relevants KPIs.[Pivot Tables](https://github.com/DataGuy-Eterniti/Amazon-Product-Review-Analysis/blob/main/Pivot%20Tables%201%20and%202.png) 

### 3. Charts and Visual Dashboard Design
- Creation of  clean, user-friendly visualizations using; Column Charts, Bar Charts, Comparison Charts (Actual vs Discounted Prices) and Organized everything into a simple, scrollable dashboard.
[Dashboard OverView](https://github.com/DataGuy-Eterniti/Amazon-Product-Review-Analysis/blob/main/Amazon%20Product%20analysis%20P1.png)

# Insights and Recommendations

## Insights
- **High Discount Impact**
    - A total of 751 products offer a 50% discount or more, showing aggressive discount strategies, especially in Health & Personal Care, Home & Kitchen, and Musical Instruments.
    - The top 3 categories with the highest average discount include:
       - Musical Instruments
      - Health & Personal Care
      - Home & Kitchen 

- **Product Engagement through Reviews**
  - **USB Cables**, **Smart Watches**, and **Smart Phones** are the ***most reviewed products***, with **USB Cables** leading at **233 reviews**.
  - Categories with **more than 500 products** like **Electronics** and **Health & Personal Care** have high potential for customer engagement.
    
- **Top-Rated Products**
  - All Top 3 Rated Products (Amazon Basics Mouse, HeadCable USB-C, and Synoviz Lag USB) received 5.0 ratings, indicating excellent customer satisfaction.

- **Price vs Rating Relationship**
  - The **average rating is highest** in the **lowest (<₦1000)** and **highest (>₦5000)** price buckets *(4.1 stars)*, suggesting perceived value is either in affordability or premium quality.

- **Potential Revenue Lookout Points**
  - **Electronics** show the **highest potential revenue (₦98,020.8K)**, making it the most lucrative category despite stiff competition.
  - This is followed by **Computers & Accessories** and **Home & Kitchen**, with substantial revenue prospects.

- **Produt Categorical Distribution**
  - Product count distribution reveals **Electronics**, **Health & Personal Care**, and **Home & Kitchen** are cconcentration categories, while **Car & Motorbike** and **Office Products** have limited products listed.

  ![image Alt](.https://github.com/DataGuy-Eterniti/Amazon-Product-Review-Analysis/blob/2e12ff63ece4d64b900cf953289de937c82e1f49/Amazon%20Product%20analysis%20P1.png)
  
  

## Recommendations

- **Focus on High-Performance Categories**, Boost visibility and promotions in **Electronics** and **Health & Personal Care**.
- Expand underrepresented categories like **Office Products** and **Car & Motorbike**.
- Sustain smart discounting where effective; avoid over-discounting highly-rated budget items.
- **Promote High-Rated Products**, Leverage reviews and testimonials from top-rated items in campaigns.
- **Improve Mid-Range Offerings** and enhance product quality in the ₦2001–₦4000 range with slightly lower ratings.

---
