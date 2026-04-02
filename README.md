# Manufacturing Production Analytics & Cost Optimization

# Overview
- This project focuses on analyzing manufacturing production data to improve operational efficiency and reduce costs. It leverages data analytics techniques to identify production bottlenecks, optimize resource utilization, and enhance profitability.
- By transforming raw production and cost data into meaningful insights, the project enables data-driven decision-making for better production planning and cost control.

# Objective
  - Analyze production performance across different units and time periods
  - Identify inefficiencies and bottlenecks in manufacturing processes
  - Optimize cost structures to improve profit margins
  - Monitor resource utilization (labor, materials, machines)
  - Provide actionable insights through an interactive dashboard

# Project Highlights
  - End-to-end manufacturing data analysis
  - Production efficiency & performance tracking
  - Cost optimization and profitability insights
  - Interactive Excel dashboard with dynamic filters
  - Identification of bottlenecks and waste areas

# Problem Statement
Manufacturing industries often face challenges like:
  - High production costs
  - Inefficient resource utilization
  - Lack of visibility into production performance
  - Difficulty in identifying bottlenecks

This project addresses these challenges by building a **data-driven analytical** system that provides clear insights into production and cost behavior.

# Dataset Description
The dataset simulates real-world manufacturing operations:
| Column Name       | Description        |
| ----------------- | ------------------ |
| Production Date   | Date of production |
| Production ID     | Id of Production   |
| ProductType       | Product type       |
| Manager           | Manager Name       |
| UnitProduced      | Number of Unit     |
| TotalCost         | Total Cost         |
| ProductionCost    | Cost Of Production |
| Gender            | Gender             |
| ProductType       | Product type       |
| Age               | Age of Manager     |
| Age Group         | Group of Age       |

<img width="1849" height="657" alt="Dataset" src="https://github.com/user-attachments/assets/6f4ecd02-6d90-4daf-9135-28b2df08d354" />

# Project Sturcture

  **1. KPIs Metrics.**
  - Total Units
  - Total Production
  - Average Cost
  - Total Production as product type


  **2. Region-wise Performance.**

  **Question :- What is the difference between West and East region performance?**

  <img width="754" height="433" alt="Region-wise Performance" src="https://github.com/user-attachments/assets/6e4dd5f3-f506-4fa8-802a-170b6182f807" />

  **Insights :-**

  - The West region is clearly the strongest market, likely due to:
      - Higher demand
      - Better market penetration
      - Strong distribution or customer base
  - The East region is underperforming, indicating:
      - Lower customer engagement
      - Possible operational or market challenges
  

  **3. Product Type Analysis.**

  **Question :- How much higher is Automobiles compared to Machinery?**

  <img width="730" height="433" alt="Product Type Analysis" src="https://github.com/user-attachments/assets/da686525-16af-4627-a4bc-370e823b32ca" />

  **Insights :-**

  - Automobiles outperform Machinery by 3,728, making it the leading product type.
  - Automobiles generate ~40% higher performance compared to Machinery.
  - The higher performance of Automobiles suggests:
      - Strong market demand
      - Higher sales volume or pricing
      - Better customer preference or product value
  - Machinery, while performing well, is not keeping pace with Automobiles.
  
  **4. Manager Performance Dashboard.**

  **Question :- Rank all managers from highest to lowest performance.**

  <img width="751" height="432" alt="Manager Perfornamce Dashboard" src="https://github.com/user-attachments/assets/47756ce3-ca6c-4548-846a-b1f46e1be29f" />

  **Insights :-**

  - Nancy Grey is the top performer, significantly ahead of all others.
  - There is a large gap between Rank 1 and Rank 2, indicating exceptional performance by Nancy.
  - The middle group (Ranks 3–7) shows relatively close performance, suggesting consistent but moderate contribution.
  - The bottom group (Ranks 8–10) are underperforming compared to others.
  - Performance is highly concentrated at the top, with Nancy Grey being a key contributor.
  - Managers in the mid-tier show stable but not outstanding performance.
  - Lower-ranked managers may require:
      - Training
      - Better targets
      - Performnace monitoring

  **5. Cost Analysis.**

  **Question :- How much higher is Automobiles cost compared to Electronics?**

  <img width="731" height="429" alt="Cost Analysis" src="https://github.com/user-attachments/assets/03728288-038a-4727-8707-b9f339e2b166" />

  **Insights :-**

  - Automobiles cost is significantly higher (~6,400 more) than Electronics.
  - This means Automobiles cost is almost 2X higher than Electronics.
  - Higher cost in Automobiles may be due to:
      - Expensive raw materials
      - Complex manufacturing processes
      - Higher operational or logistics costs
  - Electronics, being lower in cost, may have:
      - More efficient production
      - Lower material or handling costs

  **6. Gender Distibution.**

  **Question :- What proportion of the data is labeled as Unknown?**

  <img width="750" height="428" alt="Gender Distribution" src="https://github.com/user-attachments/assets/335ff3d9-4a80-4251-b63d-2d32a8d3c91f" />

  **Insights :-**

  - 9% of the total data is categorized as “Unknown”, which is a noticeable portion of the dataset.
  - This means nearly 1 out of every 11 records lacks gender identification.
  - The presence of 9% unknown data indicates:
      - Incomplete data collection
      - Customers may be skipping optional fields
      - Possible data entry or system limitations
  - This reduces the accuracy of gender-based analysis and targeting.

  **7. Monthly Production Trend.**

  **Question :- What is the total production across all months?**

  <img width="1505" height="434" alt="Monthly Production Trend" src="https://github.com/user-attachments/assets/e5c0bea5-f2e6-4dc0-97b3-954235fb9826" />

  **Insights :-**

  - The business produced approximately 34.5K units annually, indicating a moderate to strong production capacity.
  - However, production is not consistent — there are noticeable fluctuations throughout the year.
  - High production months (Feb, Mar, Nov) contribute significantly to total output.
  - Low production months (Apr, May, Jul) reduce the overall total.
  - Meaning: Total production is heavily influenced by peak months.

# Final Manufacturing Production Analytics & Cost Optimization Dashboard

<img width="517" height="610" alt="Dashboard" src="https://github.com/user-attachments/assets/08991737-11b0-496c-92f6-d79c6a286616" />

Based on the analysis, the following recommendations are made:

**Production Optimization Strategy:**
- Production shows fluctuations across months, with peaks in February and November and dips in April and July. Implement structured production planning and forecasting to maintain consistency and improve overall efficiency.

**Cost Control Strategy:**
- Categories like Automobiles and Machinery have significantly higher costs compared to others. Focus on optimizing supply chain, reducing operational inefficiencies, and improving cost management to enhance profitability.

**High-Performance Product Strategy:**
- Automobiles and Machinery are top-performing product types, contributing significantly to overall performance. Increase investment and expand operations in these categories to maximize returns.

**Regional Growth Strategy:**
- The West region dominates performance, while East and South regions underperform. Strengthen marketing, distribution, and customer engagement in low-performing regions to achieve balanced growth.

**Manager Performance Improvement:**
- Performance is highly concentrated, with Nancy Grey as the top performer. Share best practices from top performers and implement training programs to uplift mid- and low-performing managers.

**Customer Data Improvement Strategy:**
- The presence of Unknown gender (≈9%) indicates a data quality gap. Improve data collection processes to enhance customer segmentation and enable better decision-making.

**Efficiency Enhancement Strategy:**
- The production efficiency scatter analysis shows variability in performance. Focus on optimizing resource utilization and standardizing processes to improve efficiency consistency.

# Conclusion

- The manufacturing business demonstrates strong overall performance with stable production capacity and profitable operations, supported by high-performing product categories and regions. However, the analysis reveals imbalances in cost distribution, regional performance, and production consistency.
- To achieve long-term success, the business should focus on optimizing costs, improving underperforming areas, enhancing data quality, and ensuring consistent production efficiency. By implementing these strategies, the organization can achieve sustainable growth, improved operational stability, and higher profitability.
