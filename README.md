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

<details>
<summary><b>View full chart</b></summary>

#### *2011 performance*
<img width="776" height="532" alt="image" src="https://github.com/user-attachments/assets/de528281-e29b-4109-b1d7-08ab098325bb" />

#### *2012 performance*
<img width="776" height="533" alt="image" src="https://github.com/user-attachments/assets/8cc0e6c3-53c5-43b6-af3b-1dbae0a452f0" />

#### *2013 performance*
<img width="777" height="533" alt="image" src="https://github.com/user-attachments/assets/65703d97-0074-46b4-9b9b-b4c2176ac197" />

#### *2014 performance*
<img width="777" height="535" alt="image" src="https://github.com/user-attachments/assets/e77b583d-48df-4787-8f36-696ad5040f04" />
</details>

### 📌 Analysis 1. Scaling Operations & Profitability

#### *Figure 1: 4-Year Financial Trajectory (2011 vs 2014)*

<img width="341" height="248" alt="image" src="https://github.com/user-attachments/assets/1b47034f-242d-4513-80cb-2e0384e31a18" />

<img width="342" height="254" alt="image" src="https://github.com/user-attachments/assets/7bb8e02e-669f-4da6-92ed-3b77cd82a22b" />

From 2011 to 2014, the business experienced a massive scale up with **Total Revenue nearly doubling from $2.26M to $4.30M.** This expansion was remarkably healthy as **Total Profit** followed a similar upward trend, **rising from $248.9K to $504.2K.** Profit Margin remained resilient, **stabilizing between 11.4% and 11.9%,** peaking in 2013. This 4-year series confirms that this business model is not just growing in size but also maintaining strong operational efficiency

### 📌 Analysis 2. Market & Category Dynamics

#### *Figure 2: Global Market Contribution in 2014 - APAC and EU established as primary profit engines*

<img width="338" height="247" alt="image" src="https://github.com/user-attachments/assets/e8ef1790-d4ff-43f7-a2aa-ace1d9c6a782" />

The data identifies **APAC & EU as primary engines of global store success,** consistently contributing the largest shares of both revenue & profit. From a product perspective, **Technology (Phones & Copiers) & Furniture (Chairs & Bookcases)** have proven to be the **most reliable categories.** These categories have provided steady cash flow necessary to fund the company’s expansion. This series also highlights the dominance of top tier Sales Agents like Anna Andreadi, whose consistent performance over 4 years has been a cornerstone of this growth

### 📌 Analysis 3. Identify Performance Gaps – Market & Product Opportunities

#### *Figure 3: Category Profitability Comparison - Technology leads in margins while Furniture (specifically Tables) underperforms, creating a structural profit leak*

<img width="336" height="249" alt="image" src="https://github.com/user-attachments/assets/2aede201-7e78-4125-89f6-3dc19428dc73" />

Despite overall success, the 4-year trend reveals a **persistent leak in profitability caused by Tables sub-category.** While most categories improved, Tables remained trapped in **negative profit cycle with cumulative losses widening to nearly $20K by 2014.** Additionally, while the overall return rate is manageable at 4.9%, specific spikes in 2014 - such as Copiers in EU (11.56%) & Appliances in APAC (10.71%) —indicate emerging quality control or logistics issues that threaten our net margins

From a product perspective, **Furniture consistently records the lowest profit margin** across all three categories, always remaining below 8%. Additionally, Furniture has relatively **low order volume but the highest return rate** among categories, consistently above 6%, except in 2013 when it drops to 4.8%. This indicates a structural issue where the category generates **low sales efficiency while facing high return related losses,** contributing to the margin decline observed after 2013

### Recommendation
- Portfolio rationalization: execute a decisive exit strategy for the Tables category in APAC & EU. Reallocate saved capital & warehouse capacity toward Technology sector, which has shown a much higher ROI
- Operational quality audit: launch an immediate investigation into logistics & quality assurance processes for Copiers & Appliances. The goal is to reduce return rate in EU & APAC back to company average of under 5% to protect profit forecast
- Market specific expansion: double down on EMEA & EU markets which showed highest Revenue YoY growth (~45.8%) in 2014. Focus on high AOV (Average Order Value) strategies led by top performing agents to maximize value of each customer acquisition
- Incentivize high margin sales: adjust sales commission structure to favor net Profit over total revenue. This will encourage agents to pivot away from low margin items & focus on star categories identified in 2011-2014 series

### 2️⃣ Market Performance & Growth Analysis
<details>
<summary><b>View full chart</b></summary>

#### *2012 performance*
<img width="764" height="534" alt="image" src="https://github.com/user-attachments/assets/f2b0843b-5a16-47c1-9af2-e795d280e5c4" />

#### *2013 performance*
<img width="761" height="537" alt="image" src="https://github.com/user-attachments/assets/153f5dfb-e27e-46c8-86c4-cd6132ae01ef" />

#### *2014 performance*
<img width="762" height="535" alt="image" src="https://github.com/user-attachments/assets/14ba365f-bad4-492f-a02e-506ab548a55b" />
</details>

By comparing key metrics, the scale paradox was discovered: **APAC leads global revenue** ($3.5M) but achieves a **margin of only ~11.6%.** In contrast, **Canada** has the **lowest revenue** estimate at $70K but a **margin 2.3 times higher,** about 27%. Massive scale in top markets is coupled with operational inefficiency or price competition pressures far exceeding those in Canada, such as revenue growth, profit margin & customer growth. The analysis highlights how each market contributes to overall business performance & where potential opportunities or risks may emerge

### 📌 Analysis 1. Decoding Top Markets (APAC, EU, US)

<img width="1016" height="523" alt="image" src="https://github.com/user-attachments/assets/61a02355-4eed-4c9f-b361-b9ba0815ec20" />

Despite repeat customers accounting for a large proportion, profitability in this group is still hindered by three core causes:
- Profit leakage from Reverse Logistics (Returns): with **high return rates (6.5% - 8.5%),** these markets are spending a fortune on reverse shipping, inventory inspections & liquidating defective goods. Every **high value order returned** in the US **"burns" the profit** of 10 other successful orders
- Sub-optimal product mix: APAC & EU sell a **high volume of Furniture which has low profit margins** (~9%) but expensive storage, shipping costs & is easily damaged. Focusing on revenue from bulky goods has directly dragged down the overall margin
- Maintenance growth maintenance costs: despite high retention, **maintaining massive scale** & competing in these fierce markets **requires continuous budget allocation** for advertising & discounts for both old & new customers, unlike Canada where customers seek out the business themselves

### Recommendation
- Reduce return rates from 7% to <4% by apply quality control & sales consulting processes, improve operational processes (logistics, packaging, delivery), refining product descriptions & aligning customer expectations
- Deploy Loyalty Program to push Repeat Customer ratio higher, reducing dependence on advertising
- Optimize product portfolio by reducing exposure to high return or low margin products & prioritizing categories that deliver both stable demand & better profitability

### 📌 Analysis 2. Canada Case Study - High Margin Operating Model (Zero Returns, High Retention, High AOV)

<img width="768" height="504" alt="image" src="https://github.com/user-attachments/assets/9bc0fdb8-f023-4e13-bc39-95721beabb8b" />

Canada reached an ideal business state thanks to three strategic facts:

#### 2.1 Product Mix

<img width="677" height="274" alt="image" src="https://github.com/user-attachments/assets/adfce9b4-15d1-45c4-9f12-af7d6cee6d40" />

#### Looking at AOV variance:
- Technology Group: Copiers ($678.68), Phones ($560.31) & Appliances ($529.36) have **extremely high AOV & massive Profit Margins (26-35%)**
- Supplies Group: Labels ($18.34) & Fasteners ($26.64) have minimal AOV
Canada’s high Profit Margin is not achieved through across the board markups but through a **smart Product Mix.** They sell **large equipment orders** (high AOV) that bring in significant **gross profit,** while Minimal (low AOV) also maintain **healthy margins (30%+)**

#### Looking at Canada’s top Profit Margin leaders:
- Copiers (35.68% Margin on $7.4k revenue), Tables & Labels (30-35%), Envelopes, Fasteners & Accessories (29-30%)
Items like Copiers often come with maintenance packages or ink/toner. Meanwhile, small items like Envelopes or Fasteners have extremely high margins because production costs are very low compared to retail prices. Canada appears to be excelling at selling these accessory groups

#### 2.2 Synergy Between AOV and Loyalty (Repeat Customer)
Over the years, Canada’s customers have been predominantly repeat buyers, suggesting a long term trust cycle where initial purchases of small equipment in 2011 paved the way for subsequent system upgrades, such as Phones & Copiers

The fact that repeat customers return to purchase orders valued at $500 - $700 without incurring marketing costs is the reason Canada’s profit margin is surpassing other markets

#### 2.3 Structural Strengths in Minimal Return Rates, High Retention & Stable AOV
In retail, reverse logistics is a pofit erosion (shipping, damages, labor), furthermore, high AOV orders like Phones & Copiers usually carry risks of defects or customer dissatisfaction leading to returns. In Canada, **return rate remains at 0,** this proves that **customers are extremely satisfied** or that the **sales/consulting process for high value items is performing exceptionally well,** preserving 100% of the initial gross margin

As a result, Canada completed its expansion phase (2011) & shifted to profit optimization (2013-2014). This loyal customer base maintains the world's **highest margins (26-30%)** despite stagnant revenue scale. On the other hand, the **lack of new customers** in the last two years **indicates saturation.** If this repeat base churns, revenue will collapse as there is no successor generation

#### 2.4 Volume Analysis: The Trade-off
Based on data, the scale issue in Canada is clearly evident:
- Lowest revenue in the system: total revenue in Canada is only around $70K, while major markets like APAC reach up to $3.5M (50 times higher)
- Customer base: Canada has a thin customer base, this leads to high YoY growth in certain segments (Phones/Accessories up to 170-180%), but in reality, the absolute numbers remain very modest
- Saturation risk: relying almost 100% on repeat customers is a positive sign of loyalty, but it is also a trap. Without a stream of new customer acquisitions, revenue will soon hit a ceiling

### Recommendation
- Reinvest 5-10% of profit into Marketing to acquire New Customers. The goal is to build a new generation of customers to drive growth for the next period
- Test controlled expansion by gradually increasing product range while closely monitoring return rate & margin to ensure that scaling does not erode its efficiency advantage
- Expanding physical/digital touchpoint: if current operations in Canada are concentrated in only a few areas, opening additional points of sale in major cities (Toronto, Vancouver, Montreal) is essential to reach new customer segments
- Developing Omni-channel: leverage existing **0% return rate** operational process to boost E-commerce. The high quality consultation process (as proven by satisfaction indices) can be deployed via online consultation to scale up without requiring excessive physical headcount
- Leveraging high AOV: beiseds selling individual product, Canada team should bundle products into "All in one Office" solutions for Small & Medium Enterprises (SMEs). This helps increase **Basket Size** & capitalizes on the existing customer base that has a need for system upgrade
- Establish long term supply contracts instead of individual retail orders. This will solve the problem of stabilizing volume & achieving a much larger scale compared to individual customers

### 📌 Analysis 3. Regional Expansion – Performance & Growth Constraints

#### 3.1 Africa - High Efficiency Growth in Developing Markets

<img width="769" height="506" alt="image" src="https://github.com/user-attachments/assets/f1b19f9b-6efd-4542-b61c-28eb07d3cbf6" />

<img width="511" height="208" alt="image" src="https://github.com/user-attachments/assets/e0d3b822-1cdc-4b21-b8fd-57ad21e83fe8" />

Africa is demonstrating performance metrics comparable to the Canada model, characterized by **low return rates** & **stable profit margins within the 15-18% range.** Despite its smaller scale compared to major markets, Africa shows **strong performance in Office Supplies** while successfully transitioning toward Technology. A balanced mix of new & repeat customers supports a more sustainable growth trajectory compared to EMEA

#### 3.2 LATAM - Managing Profitability in Low Margin Environments

<img width="767" height="505" alt="image" src="https://github.com/user-attachments/assets/7370cbe7-baaa-4b48-bd49-364a32e9ae6b" />

While LATAM generates significant revenue, **profit margins** remain at a **critical low (~5-7%).** Root causes are:
- Product composition: the portfolio is heavily weighted toward Furniture & Standard Supplies, categories that typically yield minimal profitability
- Operational constraints: similar to APAC, LATAM is impacted by high return rates & elevated logistics costs due to geographic complexity. High price sensitivity in this region necessitates frequent discounting to maintain customer retention

### Recommendation

**For LATAM & EMEA**
- Strategic Pivot: gradually reduce the emphasis on low margin Furniture & redirect resources toward high AOV Technology categories
- Logistics Audit: identify specific regions with high return rates to optimize delivery routes or switch local carriers

**For Africa**: increase investment in Technology (Phones, Accessories) to capitalize on the existing low return rate. Africa has the potential to become the next high margin engine if it avoids the revenue growth bias trap

### 3️⃣ Product Portfolio Optimization
**Key Markets: APAC, EU, Canada | Data Period: 2011 – 2014**

<details>
<summary><b>View full chart</b></summary>

#### *2011 performance*
<img width="687" height="540" alt="image" src="https://github.com/user-attachments/assets/40df313f-c98c-484f-9b56-a3711bcb963f" />

#### *2012 performance*
<img width="687" height="538" alt="image" src="https://github.com/user-attachments/assets/c2541d3f-6fa8-4122-8cf6-64ab5b5107e1" />

#### *2013 performance*
<img width="686" height="539" alt="image" src="https://github.com/user-attachments/assets/c6e1dfe6-b268-4183-adcd-1aa5c958c82f" />

#### *2014 performance*
<img width="686" height="539" alt="image" src="https://github.com/user-attachments/assets/1337c6f6-e924-42b0-acc8-595386041c6d" />
</details>

### 📌 Analysis 1. Growth driver - Focus resources on Market Expansion (Scale-up)

<img width="845" height="520" alt="image" src="https://github.com/user-attachments/assets/c2fca791-9040-4061-bac6-d3ffa34610fb" />

Sub-categoryTechnology (Phones, Copiers) & Bookcases categories have emerged as our **primary profit engines** with 2014 profits reaching **peak levels between $40K & $50K.** This success is rooted in a quality driven growth model, for instance, **Phones maintain a very low return rate of ~4.5%,** proving that our high sales volume is not being undermined by hidden customer service costs. Furthermore, the **high demand** is confirmed by specific products like **Hewlett Fax & Epson Printers** which lead the portfolio with **growth rates above 12%,** signaling a massive opportunity for expansion in the APAC & EU regions

### Recommendation
- Allocate 60% of the next period marketing budget specifically to these high growth, low return products
- Prioritize inventory & warehouse capacity in APAC, as it currently generates the highest revenue for Copiers ($169K)

### 📌 Analysis 2. Stable Anchors: Optimizing High Volume Traded Items

<img width="849" height="521" alt="image" src="https://github.com/user-attachments/assets/8d92332d-7da9-45de-bf60-ae41d1f5c9b2" />

**Chairs, Storage & Accessories** serve as the **backbone of our daily operations,** providing massive & consistent order volumes across all years. While their profit margins are more modest than Technology, these items **act as vital traffic builders.** For example, the high density of Accessories orders on the Bubble Chart suggests these small items bring customers into our ecosystem, leading to the purchase of higher value products. In markets like Canada, these categories provide a safe & steady cash flow that keeps the business running smoothly even when other sectors fluctuate

### Recommendation
- Implement cross selling strategies by bundling Accessories with Phones or Copiers to increase the total value of every transaction
- Focus on Logistics Efficiency since Chairs & Storage are bulky, negotiating a small 1-2% reduction in shipping rates will directly boost our bottom line profit

### 📌 Analysis 3. Restructure & Filter: Protecting Capital from Losses

<img width="852" height="521" alt="image" src="https://github.com/user-attachments/assets/23c8de49-bd70-4fb5-88cf-d73634f6ef64" />

**The Tables sub-category** is identified as a **primary financial risk.** According to 2014, Tables remain the only category trapped in **negative profit zone with cumulative losses widening to nearly $20K by 2014.** Despite a relatively low return rate, the category suffers from a false growth trap where rising revenue for models like Lesro (9.5%) fails to translate into profit due to high operational & shipping costs. Similarly, **Machines** require restructuring because they are in a **High Volume, Low Profit state.** While sales are significant, the category sits dangerously close to the zero profit line. At the same time, **Copiers, Appliances & Envelopes categories show high operational risk,** with **return rates spiking above 10% in specific markets (e.g., 11.56% for Copiers in EU)** which threatens to erode overall margins

### Recommendation
- Exit Strategy: stop new stock orders for Tables in the EU & APAC markets to prevent further capital depletion & reallocate resources to profitable Technology sectors
- Margin Protection: Investigate the root causes of the high return rates in Copiers, Appliances & Envelopes to reduce logistics related losses. For Machines, a review of pricing structures or supplier costs is necessary to improve the current thin profit margins

2014 data clearly shows that the business is currently using its Technology profits to subsidize Table losses. To ensure a profitable 2015, the strategy must shift from general selling to targeted growth: reinvesting in our high quality stars while decisively removing the products that drain our resources

### 4️⃣ Sales Agents Performance Analysis

<details>
<summary><b>View full chart</b></summary>
  
#### *2012 performance*
<img width="761" height="490" alt="image" src="https://github.com/user-attachments/assets/e3aa3c82-f776-4d64-90ba-e5a295efda89" />

#### *2013 performance*
<img width="763" height="488" alt="image" src="https://github.com/user-attachments/assets/91938b9e-d7a4-4e13-a1c8-d3a5458f1d33" />

#### *2014 performance*
<img width="766" height="488" alt="image" src="https://github.com/user-attachments/assets/dfdbfcbf-173c-41c0-940a-529d00f741b1" />
</details>

### 📌 Analysis 1. Top Performers - High Value & High Quality (Investment Priority)
**Target Agents:** Anna Andreadi, Nora Preis

Anna Andreadi is the undeniable volume leader. Over the 3-year period, she successfully scaled her Total Revenue from approx $0.6M (2012) to $1.0M (2014) while keeping her return rate consistently low at ~4%. This proves her ability to manage large scale accounts without compromising quality. Nora Preis represents the highest efficiency in the team, she consistently maintains the top position in Average Order Value (AOV >$700) & has seen her profit margin climb toward 20% by 2014. Her strategy clearly focuses on high margin & premium products

### Recommendation
Appoint this group as Strategic Mentors - their portfolios should receive the highest priority for marketing support in 2015 to leverage their ability to close high value, reliable deals

### 📌 Analysis 2. High Momentum & Growth (Expansion Potential)

#### *2012 Performance*
<img width="760" height="381" alt="image" src="https://github.com/user-attachments/assets/8b952e90-2dce-4c05-87a2-ecf10d0f77fb" />

#### *2014 Performance*
<img width="767" height="383" alt="image" src="https://github.com/user-attachments/assets/b8c1a911-e186-4167-bc3a-a49f81623eb9" />

**Target Agents:** Deborah Brumfield, Alejandro Ballentine

These agents show the most dynamic movement. From 2012 to 2014, Deborah Brumfield moved from the low revenue quadrant to achieving a revenue growth rate of ~25% in 2014, with her profit margin improving year on year. Alejandro Ballentine has also shown a significant jump in total profit, moving from a near zero profit position in 2012 to becoming a solid profit contributor by 2014. They are successfully capturing new market segments

### Recommendation: 
These agents are ready for Expansion. Provide them with larger lead generation budgets & access to new sub-categories (like Technology) to help them break into top performer tier in 2015

### 📌 Analysis 3. Steady Cash Flow (Maintenance)
**Target Agents:** Chuck Magee, Anthony Jacobs

This group provides the company's safety net. Their performance is incredibly stable, Chuck Magee & Anthony Jacobs consistently sit in the center of profit & revenue charts across all three years. They maintain a healthy return rate (5-6%) and steady revenue. While they may not have explosive growth, their predictability is vital for funding other high risk operations

### Recommendation
Maintain Status Quo. Focus on retention and relationship management for their accounts. These agents are ideal for managing long-term, repeat-business clients where consistency is more valued than aggressive sales tactics

### 📌 Analysis 4. Hight risk grourp - Quality & Margin Issues (Urgent Review)

<img width="767" height="383" alt="image" src="https://github.com/user-attachments/assets/84d5bae9-1201-44aa-b98f-acff67e31148" />

**Target Agents:** Shirley Daniels, Matt Collister

This group shows persistent operational risks. Shirley Daniels has struggled with a dangerously high return rate, peaking at ~15% in 2014, which is the highest in the organization. This suggests a major gap between sales promises & product reality. Matt Collister manages decent volume, but his profit margin remains thin or stagnant. His positioning on the AOV vs. Order Growth chart shows he is working hard (high orders) but not necessarily smart (low order value), potentially over relying on discounts to hit targets

### Recommendation: 
- Shirley: must undergo a mandatory Sales Quality Audit to reduce return related logistics costs
- Matt: requires coaching on value based selling to move his focus away from high discount/low value items toward company’s star categories (Phones/Copiers)
