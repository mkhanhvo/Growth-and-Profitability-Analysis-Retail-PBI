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

### 2️⃣ Market Performance & Growth Analysis

<img width="761" height="536" alt="image" src="https://github.com/user-attachments/assets/77cd7b39-348a-48b0-ae32-b0f9237a8662" />

This section analyzes market performance over time, focusing on revenue growth, profitability & customer expansion across regions. It aims to identify differences in growth patterns, uncover performance gaps & evaluate the balance between scale and efficiency across markets.

By comparing key metrics such as revenue growth, profit margin & customer growth, the analysis highlights how each market contributes to overall business performance and where potential opportunities or risks may emerge

### 📌 Analysis 1. 2012 - Divergent Market Performance with Emerging High Growth Outliers

<img width="1019" height="250" alt="image" src="https://github.com/user-attachments/assets/5fc7b575-d076-4639-9d6c-9edfa9c85ca5" />

Canada stands out as the **only market achieving the highest revenue growth (~80%+)** while also maintaining the **highest profit margin (~43%) in 2012,** making it the only market that leads in both growth and profitability. **Customer growth** reaches 33.33% YoY, also the **highest among all markets,** however, **total order volume remains the lowest.** This indicates **early stage expansion from a small base** where strong growth is amplified by low initial scale. The combination of high margin & low volume suggests a highly efficient market, **potentially driven by favorable product mix or minimal return impact** but also raises questions about scalability as volume increases

**APAC, EU & US** remain the **top 3 markets by revenue growth** with EU outperforming the average growth level. However, unlike Canada, their growth is supported by larger revenue bases, indicating **more stable & scalable expansion.** The absence of standout profitability alongside growth in these markets suggests that scale may come with efficiency trade offs, **potentially due to higher return rates or operational costs.** Other markets show relatively stable but less significant growth, indicating limited short-term impact on overall performance

### 📌 Analysis 2. 2013 - Sustained Growth with Early Signs of Performance Divergence

<img width="1019" height="245" alt="image" src="https://github.com/user-attachments/assets/6c941a67-e24b-48db-bd6a-742dbdb749b3" />

Canada maintains the **highest profit margin** despite an 11.8% decline vs 2012. Customer growth reaches 12.5% YoY & orders increase by 25.8% YoY, however, total order volume remains the lowest across markets. This indicates that **Canada’s performance is driven more by efficiency than scale.** The combination of high margin & low volume suggests a **favorable product mix or consistently low return rates** but also raises concerns about limited scalability

**APAC, EU & US** continue to be the **top 3 markets by revenue size** with relatively stable growth. However, their **profit margins remain lower than Canada,** suggesting that higher scale may come at the **cost of efficiency.** This could be driven by higher return rates or less optimized cost structures, which dilute profitability

**Africa** records the highest revenue growth & also the highest customer growth, indicating **strong expansion potential** & still in a high-growth phase. Similarly, **EMEA** shows average revenue growth but ranks **top 2 in customer growth,** suggesting increasing market traction that may translate into future revenue growth.

### 📌 Analysis 3. 2014 - Growth Diversifies While Margin Pressure Emerges

<img width="1018" height="242" alt="image" src="https://github.com/user-attachments/assets/473ab8e8-8fcb-405c-85fb-0b0c2c10344f" />

**Canada** continues to have the **highest profit margin** despite a further decline of 3.3% vs 2013, while still maintaining the **lowest revenue & growth contribution.** Customer growth also decreases by 11.1% vs 2013, indicating **slowing momentum.** This reinforces the pattern of a **high margin but low scale market,** suggesting that Canada’s profitability is driven by efficiency rather than volume. However, the consistent decline in both margin & customer growth raises **concerns about the sustainability of this performance**

**EMEA** achieves the **highest revenue growth** at 45.8% YoY & ranks **top 2 in customer growth,** just behind Africa. This indicates strong market expansion & improving demand. Given both customer & revenue growth are increasing, EMEA appears to be **transitioning from a developing market into a scalable growth driver**

**APAC, EU, & US** remain the **top 3 markets by revenue** but their profit margins are consistently lower than Canada despite higher scale. EU shows the strongest growth among the top 3 with ~37.26% YoY revenue growth, while customer growth remains moderate across all three markets. This suggests that growth in these markets is likely **driven more by increased purchasing behavior** rather than strong customer acquisition & may come with efficiency trade offs

**LATAM** achieves above average revenue & remains in the **top 3 by order volume** but continues to have **low profit margin**, only slightly higher than EMEA. This indicates that while the market has scale, it lacks profitability, potentially due to **unfavorable product mix or higher operational costs,** limiting its overall contribution to profit

### 🌍 Overall observation – Structural Trade off Between Scale & Profitability

#### *High Profit Margin but Low Revenue Contribution in Canada*

<img width="677" height="271" alt="image" src="https://github.com/user-attachments/assets/500a37f9-b44e-4a6d-8c46-831308a6c876" />

#### *High Revenue Markets Show Lower Profit Margins*

<img width="676" height="269" alt="image" src="https://github.com/user-attachments/assets/a65336e1-8fe1-4254-8feb-8df181958bfa" />

One **potential explanation** for a market exhibiting high profit margin but low revenue is a **consistently low return rate.** A near-zero return rate reduces reverse logistics costs, minimizes refund related losses & protects realized revenue, all of which contribute directly to higher profitability. In contrast, markets with **higher return rates** (e.g., ~6%–8% in APAC and EU) **may experience margin erosion** due to additional handling costs, product write offs & operational inefficiencies

In the case of Canada, its **0% return rate** across multiple years suggests that strong margin performance **may be driven by factors** such as better product market fit, higher customer satisfaction or more selective purchasing behavior. However this could also indicate a narrower or more premium focused product offering which limits overall transaction volume & constrains revenue scale

Additionally, a low return rate may reflect stricter sales conditions, lower promotional intensity, or more informed customers, all of which can improve profitability but reduce purchase frequency or customer acquisition. **This creates a structural trade & off where operational efficiency and margin optimization come at the expense of scale & growth**

### Recommendation
- **Reduce return rates in high volume markets** (APAC, EU) by improving product quality, refining product descriptions & aligning customer expectations. With return rates currently around ~6%–8%, even small reductions can significantly improve profit margins at scale
- Analyze & replicate Canada’s low return model (~0%) by **identifying key drivers** such as **product mix, customer segment or purchase behavior** & selectively applying these practices to other markets where feasible
- **Optimize product portfolio** in core markets by reducing exposure to high return or low margin products & prioritizing categories that deliver both stable demand & better profitability
- **Improve operational processes** (logistics, packaging, delivery) to minimize product damage & mismatch, which are common drivers of returns and hidden cost leakage
- **Test controlled expansion in Canada** by gradually increasing product range or marketing investment while closely monitoring return rate & margin to ensure that scaling does not erode its efficiency advantage
- **Implement return rate monitoring** as a core KPI across markets, enabling early detection of margin risks & supporting more data driven decisions on pricing, promotions & product strategy
