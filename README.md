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

<img width="761" height="534" alt="image" src="https://github.com/user-attachments/assets/1364d67d-d58d-4c0b-a5dc-f1793f0599ed" />

By comparing key metrics, the scale paradox was discovered: APAC leads global revenue ($3.5M) but achieves a margin of only ~11.6%. In contrast, Canada has the lowest revenue (~$70K) but a margin 2.3 times higher (~27%). Massive scale in top markets is coupled with operational inefficiency or price competition pressures far exceeding those in Canada, such as revenue growth, profit margin & customer growth. The analysis highlights how each market contributes to overall business performance & where potential opportunities or risks may emerge

### 📌 Analysis 1. Decoding Top Markets (APAC, EU, US)

<img width="1018" height="249" alt="image" src="https://github.com/user-attachments/assets/95bec054-6b55-4deb-8baf-8eb14c01e3fc" />

Despite repeat customers accounting for a large proportion, profitability in this group is still hindered by three core causes:
- Profit leakage from Reverse Logistics (Returns): with **high return rates (6.5% - 8.5%),** these markets are spending a fortune on reverse shipping, inventory inspections & liquidating defective goods. Every **high value order returned** in the US **"burns" the profit** of 10 other successful orders
- Sub-optimal Product Mix: APAC & EU sell a **high volume of Furniture which has low profit margins** (~9%) but expensive storage, shipping costs & is easily damaged. Focusing on revenue from bulky goods has directly dragged down the overall margin
- Maintenance Growth Maintenance Costs: despite high retention, **maintaining massive scale** & competing in these fierce markets **requires continuous budget allocation** for advertising & discounts for both old & new customers, unlike Canada where customers seek out the business themselves

### Recommendation
- Reduce return rates from 7% to <4% by apply quality control & sales consulting processes, improve operational processes (logistics, packaging, delivery), refining product descriptions & aligning customer expectations
- Deploy Loyalty Program to push Repeat Customer ratio higher, reducing dependence on advertising
- Optimize product portfolio by reducing exposure to high return or low margin products & prioritizing categories that deliver both stable demand & better profitability

### 📌 Analysis 2. Canada Case Study - High Margin Operating Model (Zero Returns, High Retention, High AOV)

Canada reached an ideal business state thanks to three strategic facts:

**2.1 Product Mix**
**Looking at AOV variance:**
- Technology Group: Copiers ($678.68), Phones ($560.31) & Appliances ($529.36) have **extremely high AOV & massive Profit Margins (26-35%)**
- Supplies Group: Labels ($18.34) & Fasteners ($26.64) have minimal AOV
Canada’s high Profit Margin is not achieved through across the board markups but through a **smart Product Mix.** They sell **large equipment orders** (high AOV) that bring in significant **gross profit,** while Minimal (low AOV) also maintain **healthy margins (30%+)**

**Looking at Canada’s top Profit Margin leaders:** Copiers (35.68% Margin on $7.4k revenue), Tables & Labels (30-35%), Envelopes, Fasteners & Accessories (29-30%)
Items like Copiers often come with maintenance packages or ink/toner. Meanwhile, small items like Envelopes or Fasteners have extremely high margins because production costs are very low compared to retail prices. Canada appears to be excelling at selling these accessory groups

**2.2 Synergy Between AOV and Loyalty (Repeat Customer)**
Over the years, Canada’s customers have been predominantly repeat buyers, suggesting a long term trust cycle where initial purchases of small equipment in 2011 paved the way for subsequent system upgrades, such as Phones & Copiers

The fact that repeat customers return to purchase orders valued at $500 - $700 without incurring Marketing costs is the reason Canada’s profit margin is surpassing other markets

**2.3 Structural Strengths in Minimal Return Rates, High Retention & Stable AOV**
In retail, reverse logistics is a pofit erosion (shipping, damages, labor), furthermore, high AOV orders like Phones & Copiers usually carry risks of defects or customer dissatisfaction leading to returns. In Canada, **return rate remains at 0,** this proves that **customers are extremely satisfied** or that the **sales/consulting process for high value items is performing exceptionally well,** preserving 100% of the initial gross margin.

As a result, Canada completed its expansion phase (2011) & shifted to profit optimization (2013-2014). This loyal customer base maintains the world's **highest margins (26-30%)** despite stagnant revenue scale. On the other hand, the **lack of new customers** in the last two years **indicates saturation.** If this repeat base churns, revenue will collapse as there is no successor generation

### Recommendation
- Reinvest 5-10% of profit into Marketing to acquire New Customers. The goal is to build a new generation of customers to drive growth for the next period
- Test controlled expansion by gradually increasing product range while closely monitoring return rate & margin to ensure that scaling does not erode its efficiency advantage

### 📌 Analysis 3. Regional Expansion – Performance & Growth Constraints

**3.1 Africa - High Efficiency Growth in Developing Markets**

Africa is demonstrating performance metrics comparable to the Canada model, characterized by low return rates (3-4%) & stable profit margins within the 15-18% range. Despite its smaller scale compared to major markets, Africa shows strong performance in Office Supplies while successfully transitioning toward Technology. A balanced mix of new & repeat customers supports a more sustainable growth trajectory compared to EMEA

**3.2 LATAM - Managing Profitability in Low Margin Environments**

While LATAM generates significant revenue, profit margins remain at a critical low (~5-7%). Root causes are:
- Product Composition: the portfolio is heavily weighted toward Furniture & Standard Supplies, categories that typically yield minimal profitability
- Operational Constraints: similar to APAC, LATAM is impacted by high return rates & elevated logistics costs due to geographic complexity. High price sensitivity in this region necessitates frequent discounting to maintain customer retention

### Recommendation

**For LATAM & EMEA**
- Strategic Pivot: gradually reduce the emphasis on low margin Furniture & redirect resources toward high AOV Technology categories
- Logistics Audit: identify specific regions with high return rates to optimize delivery routes or switch local carriers

**For Africa**: increase investment in Technology (Phones, Accessories) to capitalize on the existing low return rate. Africa has the potential to become the next high margin engine if it avoids the revenue growth bias trap
