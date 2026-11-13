# E-commerce-Analysis
Analyzing Simulated E-commerce Operations of a Fashion Company Through Data Visualization

## Dataset Description
The dataset simulates the operations of an e-commerce fashion company from July 4, 2012, to December 31, 2022. It consists of 15 CSV files, containing approximately 3 million rows and 96 columns.\\

**Data Source:** [Kaggle – Datathon 2026 Round 1](https://www.kaggle.com/competitions/datathon-2026-round-1)

## Analysis Areas (2/4)
- **Sales Performance Analysis:** Evaluate revenue trends, sales growth, and product and category performance.
- **Returns Analysis:** Examine return rates, refund amounts, and return patterns.
- **Customer Behavior Analysis:** Analyze customer purchasing patterns and preferences.
- **Inventory Analysis:** Evaluate stock levels, sales volume, and stockout patterns.

## I. Sales Performance Analysis:
<img width="1522" height="860" alt="image" src="https://github.com/user-attachments/assets/7757efcf-bb31-416f-9063-60c7a3aa399b" />

### 1. Overview
The Sales Performance Dashboard provides an overview of the company's e-commerce performance, focusing on revenue growth, profitability, and sales distribution.

It enables users to compare current-year performance against the previous year and explore business performance across multiple dimensions through interactive filters.

#### Key analytical objectives:
- Monitor overall sales performance and financial KPIs.
- Evaluate revenue and profit trends over time.
- Identify high-performing product categories and customer segments.
- Analyze regional sales distribution and order source contributions.
- Identify potential opportunities to improve profitability and sustain revenue growth.

### 2. Key Performance Indicators (KPIs)
The dashboard tracks six core business metrics:


#### Key Performance Indicators (2022)

| KPI | 2022 | YoY Change | Description |
|---|---:|---:|---|
| **Gross Revenue** | $993.67M | +11.1% | Total revenue generated from fulfilled sales before discounts and returns. |
| **Sale Dilution Rate** | 7.99% | -6.6% | Percentage of gross revenue lost through discounts and returns. |
| **Gross Profit** | $82.30M | +91.8% | Net Revenue remaining after deducting COGS. |
| **Total Customers** | 21.86K | +1.5% | Number of unique customers. |
| **Total Orders** | 30.39K | +2.4% | Total number of orders. |
| **AOV** | $32.70K | +8.4% | Average gross revenue generated per order. |

_LY represents the previous-year value, while YoY indicates the year-over-year percentage change._

### 3. Key Visualizations & Business Insights

#### 3.1 Monthly Revenue/Profit Trend

- **Revenue showed positive growth, while profit improved at a significantly faster rate.**
  - Gross revenue reached $993.67M, increasing by 11.1% year-over-year, while Gross Profit rose significantly by 91.8%, from $42.90M to $82.30M, indicating improved profitability.
  - April recorded the highest monthly revenue at approximately $124.93M; however, its profit ranked only 8th at $5.04M, while July and December reported negative profits.
  - Revenue peaked during March–June before gradually declining toward the end of the year.
  - December recorded the lowest monthly revenue at approximately $33.35M.
  
  **Discount Rate - COGS vs. Profit Margin**
  
    <img width="521" height="526" alt="image" src="https://github.com/user-attachments/assets/9d27fa35-0204-46dd-b801-da77409f26be" />

    - **High Discounts – Weak Profitability:** December recorded the highest Discount Rate at 20.00%, accompanied by a COGS Rate of 97.26% and a negative Profit Margin of -21.78%. July showed a similar pattern, with an 11.82% Discount Rate and a -6.77% Profit Margin.
    
    - **Lower Discounts – Stronger Profitability:** Months with little or no discounts generally achieved higher Profit Margins. February and May, with no recorded discounts, achieved Profit Margins of 17.37% and 17.46%, respectively.
    
    - **High COGS Rates During Discount Periods:** Months with higher discounts also tended to have higher COGS Rates. December reached 97.26%, compared with approximately 79%–80% in months without discounts. This suggests that both discount expenses and product cost structure may have contributed to the deterioration in profitability.
    
    - **Potential Trade-off Between Sales Growth and Profitability:** Although discount campaigns may help stimulate demand, the observed monthly results raise concerns about whether the additional revenue generated was sufficient to compensate for reduced selling prices and high product costs.



- **Revenue growth was primarily driven by higher product prices and average order value rather than an increase in sales volume.**
  - Average selling price per product increased from $6.32K to $6.89K (+9.0%), while the average number of products per order remained nearly unchanged at 4.75 compared to 4.77 in the previous year.
  - Total Orders grew by 2.4%, from 29.7K to 30.39K orders.
  - AOV increased by 8.4%, from $30.2K to $32.7K per order, indicating that higher spending per order was the main driver of revenue growth.


    | Metric | 2021 | 2022 | YoY Change |
    |---|---:|---:|---:|
    | Average Selling Price per Product | $6.32K | $6.89K | +9.0% |
    | Average Products per Order | 4.77 | 4.75 | -0.4% |
    | Total Orders | 29.70K | 30.39K | +2.4% |
    | Average Order Value (AOV) | $30.2K | $32.7K | +8.4% |


#### 3.2 Revenue by category


- **Streetwear dominates revenue contribution, but sales volume does not always translate into higher profitability.**
  - Streetwear accounts for 83.87% of total revenue, highlighting the company's heavy reliance on a single product category.
  - Everyday stands out as a Star segment, combining above-average revenue and profit margin with substantial sales volume, making it a strong candidate for further investment.
  - Balanced generates high revenue and has the largest sales volume among the segments, but its profit margin remains below the overall average (8.28%), indicating potential issues with pricing, product costs, or discount strategies.
  - Meanwhile, segments such as Activewear, Trendy, and All-weather demonstrate relatively high profit margins despite lower revenue contributions, suggesting opportunities to expand sales and diversify revenue sources.
  - The company should prioritize profitable sales growth rather than focusing solely on increasing sales volume.


    
    **Recommendations**
    
    | Segment | Recommended Strategy |
    |---|---|
    | **Everyday** | Maintain performance and scale sales. |
    | **Balanced** | Optimize pricing, COGS, and discounts to improve profitability. |
    | **Activewear** | Explore opportunities to increase sales volume. |
    | **Trendy** | Expand demand through targeted marketing. |
    | **All-weather** | Scale sales while maintaining profit margin. |
    | **Premium, Standard, Performance** | Review product positioning and profitability. |



#### 3.3. Revenue by Region

- **East is the largest revenue-contributing region, while West achieves the highest profit margin.**

  | Region | Gross Revenue | Gross Profit | Total Customers | Total Orders | AOV |
  |---|---:|---:|---:|---:|---:|
  | East | $462.60M | $37.45M | 10,457 | 13.94K | $33.19K |
  | Central | $327.32M | $24.20M | 6,918 | 9.48K | $34.54K |
  | West | $203.75M | $20.65M | 4,484 | 6.97K | $29.23K |

  - **East – Revenue Leader**
    - Generated $462.60M, accounting for approximately 46.6% of total revenue.
    - Recorded the highest number of customers (10,457) and orders (13.94K), indicating that its revenue advantage is primarily driven by a larger customer base and higher sales volume.
    - Achieved the highest Gross Profit at $37.45M.

  - **Central – Highest Average Order Value**
    - Ranked second in Gross Revenue at $327.32M.
    - Recorded the highest AOV at $34.54K per order, suggesting higher average spending per transaction despite having fewer customers and orders than East.

  - **West – Highest Profit Margin**
    - Generated $203.75M in Gross Revenue, representing approximately 20.5% of total revenue.
    - Achieved $20.65M in Gross Profit, resulting in an estimated profit margin of 10.1%, higher than East (8.1%) and Central (7.4%).
    - Recorded the lowest AOV at $29.23K, suggesting opportunities to increase average spending per order.

  **Recommendations**

  | Region | Recommended Strategy |
  |---|---|
  | **East** | Maintain effective sales strategies and strengthen customer retention to sustain its leading revenue contribution. |
  | **Central** | Leverage its relatively high AOV to expand the customer base and increase order volume. |
  | **West** | Increase customer acquisition, order volume, and AOV while maintaining its strong profit margin. |
  | **Overall** | Develop region-specific strategies to balance revenue growth and profitability rather than focusing exclusively on the highest-revenue region. |




#### 3.4. Revenue by Order Source

- **Organic Search and Paid Search are the two largest revenue-contributing order sources.**

  | Order Source | Revenue Share |
  |---|---:|
  | Organic Search | 27.51% |
  | Paid Search | 21.79% |
  | Social Media | 20.25% |
  | Email Campaign | 12.03% |
  | Referral | 10.34% |
  | Direct | 8.08% |

  - **Organic Search – Largest Revenue Contributor**
    - Accounts for 27.51% of total revenue, making it the largest order source.
    - Highlights the importance of organic traffic and search visibility in generating sales.

  - **Paid Search – Second Largest Revenue Contributor**
    - Contributes 21.79% of total revenue.
    - Represents a significant source of sales alongside Organic Search.

  - **Social Media – Third Largest Revenue Contributor**
    - Accounts for 20.25% of total revenue.
    - Together, Organic Search, Paid Search, and Social Media contribute 69.55% of total revenue, indicating that these three sources play a dominant role in revenue generation.

  **Recommendations**

  | Order Source | Recommended Strategy |
  |---|---|
  | **Organic Search** | Maintain SEO investments and improve search visibility to sustain organic traffic and revenue. |
  | **Paid Search** | Evaluate customer quality through AOV, conversion rate, and customer retention. |
  | **Social Media** | Optimize campaigns and assess their contribution to customer acquisition and repeat purchases. |
  | **Email Campaign** | Evaluate campaign performance and identify opportunities to encourage repeat purchases. |
  | **Referral** | Strengthen referral programs to attract new customers through existing customer networks. |
  | **Direct** | Improve brand awareness and customer loyalty to encourage direct visits and purchases. |
  | **Overall** | Monitor customer retention and purchasing behavior across order sources to identify differences in customer value. |

  **Data Limitations**

  - The analysis reflects revenue contribution by order source but does not measure marketing efficiency or profitability.
  - Further evaluation requires additional metrics, including Marketing Spend, Customer Acquisition Cost (CAC), and Conversion Rate.


## II. Returns Analysis

<img width="1605" height="860" alt="image" src="https://github.com/user-attachments/assets/a0aeaac4-2a9f-4c0e-b760-09c4eb2cdd09" />


### 1. Overview

The Returns Analysis Dashboard provides an overview of the company's product return performance, focusing on return rates, refund amounts, return reasons, and product-level return patterns.

It enables users to monitor return performance against the previous year and identify potential issues across different time periods, product categories, and segments through interactive filters.

**Key Analytical Objectives:**
- Monitor return-related KPIs, including Return Amount, Return Rate, and Sale Dilution Rate.
- Evaluate monthly return trends and identify periods with unusually high return rates.
- Identify the main reasons contributing to product returns.
- Compare return performance across product categories and segments.
- Identify high-risk products with significant revenue contributions and return rates.
- Explore opportunities to reduce returns and improve product quality and customer satisfaction.

### 2. Key Performance Indicators (KPIs)

The dashboard tracks five core business metrics to evaluate return performance and its impact on revenue.

**Key Performance Indicators (2022)**

| KPI | 2022 | YoY Change | Description |
|---|---:|---:|---|
| Gross Revenue | $993.67M | +11.1% | Total revenue generated from fulfilled sales before discounts and returns. |
| Sale Dilution Rate | 8.10% | -5.1% | Percentage of gross revenue lost through discounts and returns. |
| Discount | $44.75M | +1.5% | Total discount amount applied to sales. |
| Return Amount | $35.71M | +10.7% | Total monetary value refunded for returned products. |
| Return Rate | 3.59% | -0.3% | Percentage of fulfilled sales quantity that was returned. |

*LY represents the previous-year value, while YoY indicates the year-over-year percentage change.*

**Key Insight:**
- **Stable Return Rate, but Increasing Refunds:** Return Rate remained relatively stable year-over-year. However, the additional $3.46M in refunds remains a significant concern, equivalent to approximately 4.26% of the company's $81.21M Gross Profit. Reducing these return-related losses could therefore create a meaningful opportunity to improve profitability.

### 3. Key Visualizations & Business Insights

#### 3.1. Return Rate by Month

- **Monthly Extremes:** February recorded the lowest Return Rate at 2.18%, while November peaked at 5.03%, the highest throughout the year.
- **Seasonal Trend:** Return Rates were generally higher in the second half of the year, suggesting an increase in product returns toward year-end.

#### 3.2. Return Rate by Reason

**Key Insights**

- **Wrong Size – Leading Return Reason:** Wrong Size accounted for approximately 36.6% of returns across the five categories, making it the leading return reason in 2022. This suggests a potential mismatch between customers' sizing expectations and actual product fit.
  - **Saigonflex UM-54** recorded the highest return quantity (320 units) and the largest return amount ($3.49M), making it a priority for further investigation.
- **Late Delivery – Fastest YoY Growth:** Despite having the lowest return quantity among the five reasons, Late Delivery recorded the highest YoY increase at 14.47%, indicating a growing delivery-related issue.

**YoY Change by Return Reason**

| Return Reason | YoY Change |
|---|---:|
| Wrong Size | +13.65% |
| Late Delivery | +14.47% |
| Changed Mind | +1.16% |
| Defective | -2.08% |
| Not as Described | -4.03% |

**Recommendations**

**1. Improve Size and Fit Information**
- Provide detailed size charts for each product.
- Include model measurements and the size worn by the model.
- Leverage customer reviews to provide additional feedback on product fit.
- Identify products with unusually high Wrong Size return rates, prioritizing Saigonflex UM-54 for further investigation.

**2. Improve Delivery Performance**
- Monitor late delivery rates by geographic region and shipping provider.
- Identify delivery routes with consistently high Late Delivery rates.
- Investigate potential causes of delays to improve delivery reliability and reduce delivery-related returns.

#### 3.3. Return Rate by Category and Segment

Return Rates were relatively consistent across product categories, ranging from 3.54% to 4.04%. The relatively small differences across categories suggest that return-related issues may be concentrated in specific products rather than being driven by entire product categories. Further product-level investigation is therefore necessary to identify the main sources of return risk.

#### 3.4. Product-level Return Analysis

**1. Return Amount Concentration**

- **Saigonflex UM-54 – Highest Return Amount:** This product recorded the highest Return Amount among all products, at approximately $3.5M, making it the most significant contributor to product-level return losses.
- **Concentration of Return Amount:** Several other Saigonflex products also appeared among the top 10 products by Return Amount, suggesting that return-related losses may be concentrated in particular products or product lines.

**2. Return Rate Distribution**

- **Most Products Have Relatively Low Return Rates:** The histogram shows that 357 products fall within the 0%–2% Return Rate range, representing the largest group.
- **High Return Rate Products:** A total of 116 products have Return Rates above 6%, including 57 products exceeding 10%.
- **Investigation Priority:** Products with exceptionally high Return Rates should be investigated further, particularly when they also generate substantial Gross Revenue or Return Amount.

**3. Product Risk Classification**

Products were classified into four risk groups using two financial indicators:

- **Return Rate:** Return Amount / Gross Revenue.
- **Revenue Level:** Gross Revenue compared with Median Gross Revenue.

The classification reveals four distinct product groups:

| Risk Group | Business Interpretation |
|---|---|
| High Return – High Revenue | High financial exposure; highest investigation priority. |
| High Return – Low Revenue | High return ratio but relatively limited revenue exposure. |
| Low Return – High Revenue | Strong revenue contribution with relatively controlled return losses. |
| Low Return – Low Revenue | Lower financial exposure under current performance. |

**Key Insights**

- **Low Return – Low Revenue (Largest Group):** This group accounts for the largest number of products, indicating that most products generate relatively low revenue while maintaining low return rates. Although their individual financial contribution is limited, they represent a large portion of the product portfolio.
- **High Revenue Products – Mixed Return Performance:** Low Return – High Revenue and High Return – High Revenue contain relatively similar numbers of products. This indicates that a considerable number of high-revenue products experience elevated return rates, highlighting an opportunity to improve return performance among key revenue-generating products.
- **High Return – Low Revenue (Smallest Group):** This group contains the fewest products, suggesting that products with both low revenue and high return rates represent a relatively limited portion of the portfolio.
- **Category Distribution:** Streetwear contributes the largest number of products across the risk groups, while the other categories have smaller contributions. This suggests that product-level investigation within Streetwear may cover a substantial portion of the portfolio.

**Recommendations**

**1. Prioritize High-Revenue Products with High Return Rates**

The number of products in the High Return – High Revenue group is comparable to that in the Low Return – High Revenue group. This indicates that elevated return rates are not limited to a small number of isolated products but also affect a considerable portion of revenue-generating products.

- Identify products with the highest Return Amount within the High Return – High Revenue group.
- Prioritize these products for further investigation and improvement.
- Investigate potential causes of returns to reduce financial losses while protecting revenue contributions.

**2. Optimize the Large Low-Revenue Product Portfolio**

Low Return – Low Revenue represents the largest product group. Although these products have relatively low return rates, their large number may lead to resources being spread across products with limited financial contributions.

- Evaluate product profitability and market demand to identify underperforming products.
- Prioritize resources toward products with stronger growth potential.
- Consider optimizing or discontinuing products with consistently low revenue and limited market demand.
