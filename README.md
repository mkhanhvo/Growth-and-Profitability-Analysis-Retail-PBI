## 📊 Growth & Profitability Analysis | Retail | PBI

### Author: Vo Tran Mai Khanh
### Date: 03/2026
### Tools Used: PBI

## 📌 Background & Overview

### 📖 Objective
- Evaluate overall business performance over four-year period to understand growth trends in revenue, profitability & operational efficiency
- Assess the development potential of markets, products & sales agents to identify high performing areas for scaling & underperforming areas for optimization or adjustment
- Detect potential issues or inefficiencies in performance & investigate underlying drivers to understand their root causes
- Provide data driven direction for strategic decisions, including investment prioritization, performance improvement & resource allocation

### 👤 Who is this project for?
- Executive Leadership (BOD) – to gain a holistic view of business performance, assess growth sustainability & support strategic decision making
- Business Development / Strategy Team – to evaluate market potential, identify growth opportunities & prioritize investment and expansion strategies
- Sales Management – to monitor performance across markets & sales agents, drive actions to scale high performers or improve underperforming areas
- Product Team – to evaluate product performance, optimize product mix & address profitability or return-related issues
- Operations Team – to identify operational inefficiencies impacting profitability, such as logistics or return handling & improve execution

### 👤 Client Background
Global Superstore is a fictional, large-scale global online retailer based in New York that serves as a common dataset for data analysis, business intelligence (BI) & supply chain modeling. It operates as a one-stop shop with a broad product catalog catering to a diverse, worldwide clientele

### 📊 Data Source  
- Source: publicly available retail dataset from Kaggle   
- Size: 51,290 records covers over 147 countries, providing data on product categories, sales, profit & customer information
- Format: .xls

### 📊 Data Structure & Relationships

#### 1️⃣ Tables Used: 
- Orders: fact table contains 51,290 records, each representing a single transaction line item from a global retail business. It captures order level, customer level & product level information across multiple markets
- Dimensions tables: date, product, people, return, geography

#### 2️⃣ Table Schema & Data Snapshot

<details>
<summary><b>Tabe 1: Order</b></summary>
<img width="767" height="96" alt="image" src="https://github.com/user-attachments/assets/494dad92-4249-406d-802a-02990c88c89f" />
</details>

<details>
<summary><b>Tabe 2: Date</b></summary>
<img width="563" height="595" alt="image" src="https://github.com/user-attachments/assets/5b7a3396-ee63-4461-bede-f929e4315404" />
</details>

<details>
<summary><b>Tabe 3: Product</b></summary>
<img width="616" height="110" alt="image" src="https://github.com/user-attachments/assets/112bf410-c7f1-4284-ad89-43d60b2f86e8" />
</details>

<details>
<summary><b>Tabe 4: People</b></summary>
<img width="175" height="299" alt="image" src="https://github.com/user-attachments/assets/a08eeefe-4b23-4d5b-beb8-bedf622a5409" />
</details>

<details>
<summary><b>Tabe 5: Return</b></summary>
<img width="173" height="593" alt="image" src="https://github.com/user-attachments/assets/02786cbd-6e71-4699-a0fd-97c38dcb2f39" />
</details>

<details>
<summary><b>Tabe 6: Geography</b></summary>
<img width="478" height="97" alt="image" src="https://github.com/user-attachments/assets/36012529-b66f-44a7-813e-f22a90a2a752" />
</details>

#### 3️⃣ Data Relationships: 

<img width="623" height="502" alt="image" src="https://github.com/user-attachments/assets/51df859c-b2e9-4389-92ab-f61a441fee18" />

## 📊 Key Insights & Visualizations 

### 1️⃣ Sales Performance & Growth Overview

### 📌 Analysis 1. Analyze Growth Drivers – Revenue, Profit & Customer Dynamics

<img width="780" height="533" alt="image" src="https://github.com/user-attachments/assets/528eb09d-41b3-46e8-be9c-0a257137e81a" />

The business shows consistent year over year growth with revenue **increasing steadily from 18.5% to over 25%.** Profit also grows by **more than 20% annually** with the highest increase of **32.4% in 2013.** Profit margin slightly declines by 1.9% in 2014 compared to the previous year, indicating a minor efficiency drop

This growth is **primarily driven by order volume** which increases by **more than 20% each year,** while customer growth remains below 5%. This suggests that existing customers are purchasing more frequently, indicating **strong repeat buying behavior** but new customer acquisition is relatively slow

### Recommendations
Focus on accelerating customer acquisition to sustain long term growth while maintaining strong engagement & retention strategies for existing customers

### 📌 Analysis 2. Evaluate Growth Efficiency – Profitability & Return Impact

<img width="341" height="498" alt="image" src="https://github.com/user-attachments/assets/7c642150-e834-455f-8ac8-d364b24e1791" />

Order volume **grows significantly by 51.37%** from **2011 to 2013** & profit margin **improves by 8.44% **during the same period, confirming a **positive impact from increased sales volume.** However, after 2013, although order volume continues to rise, profit margin begins to decline. At the same time, return rate decreases, indicating that **returns are not the primary driver of margin decline**

Customer growth remains very low, creating a potential risk for future growth sustainability. Meanwhile, return rate trends still require attention, as any increase could negatively impact profitability

### Recommendation
Investigate other cost drivers such as discounting, pricing strategy & product mix. At the same time, prioritize customer acquisition & monitor return related issues such as logistics quality, product condition after delivery & customer service

### 📌 Analysis 3. Identify Performance Gaps – Market & Product Opportunities

<img width="677" height="497" alt="image" src="https://github.com/user-attachments/assets/8215b075-c8f1-499d-bfbf-f4e2d43ae419" />

**APAC & EU** contribute the **largest share of revenue & profit,** while **Canada stands out** with **significantly higher profit margin** despite having the lowest revenue & profit contribution, indicating a high potential but underdeveloped market. In terms of growth, **Canada (2012), Africa (2013) & EMEA (2014)** show the highest revenue YoY increases, **suggesting strong future expansion opportunities** despite not being top contributors currently

From a product perspective, **Furniture consistently records the lowest profit margin** across all three categories, always remaining below 8%. Additionally, Furniture has relatively **low order volume but the highest return rate** among categories, consistently above 6%, except in 2013 when it drops to 4.8%. This indicates a structural issue where the category generates **low sales efficiency while facing high return related losses,** contributing to the margin decline observed after 2013

### Recommendation
Prioritize scaling high-margin markets such as Canada and high-growth regions like Africa and EMEA. For products, reassess the Furniture category by reviewing pricing, cost structure, and product quality to reduce returns and improve profitability


