# 🛍️ Retail Sales & Customer Insights Dashboard | Excel

## 📌 Project Overview

This project analyzes retail sales data in Microsoft Excel to
understand what drives revenue, which customers are most valuable, which
products perform best, and which shopping malls generate the most
revenue.

The main goal was to move beyond charts and answer a simple business
question:

What is happening in the business, why does it matter, and what can
the business do about it?

The analysis was completed using Pivot Tables, Pivot Charts, Slicers,
Filters, and calculated metrics.

## 🎯 Business Questions

### This analysis focuses on:

Which categories generate the most revenue?

Which customer groups generate the most revenue?

Which malls perform best?

Which payment methods are most commonly used?

Which months perform best and worst?

Does high quantity always mean high revenue?

Where is revenue concentrated?

What actions could help improve business performance?

## 📊 Dataset

The dataset contains retail transaction information.

Column             Meaning

Customer_Id      Customer identifier
Gender           Customer gender
Age              Customer age
Category         Product category
Quantity         Number of units purchased
Price            Product price
Revenue          Revenue from the transaction
Payment_Method   Payment method used
Invoice_Date     Transaction date
Month            Transaction month
Day              Day of the week
Shopping_Mall    Shopping mall
Age_Group        Customer age group
Year             Transaction year

## 🛠️ Tools Used

Microsoft Excel

Pivot Tables

Pivot Charts

Slicers

Filters

KPI calculations

Data analysis

Dashboard design

## 📌 Key KPIs

KPI                            Result

Total Revenue                 ₹251.51M

Total Transactions              99.46K

Average Order Value (AOV)       ₹2.53K

Note: There is no separate Order ID in the dataset, so transaction
count is based on the available Customer ID records.

### 🔎 Key Business Insights

1. Most revenue comes from three categories

Category                 Revenue

Clothing                 ₹114.00M

Shoes                    ₹66.55M

Technology               ₹57.86M

Cosmetics                 ₹6.79M

Toys                      ₹3.98M

Food & Beverage           ₹0.85M

Books                     ₹0.83M

Souvenir                  ₹0.64M


## What I found

Clothing, Shoes, and Technology generate about 95% of total revenue.

Clothing is the clear leader with ₹114M in revenue.

### Why this matters

The business depends heavily on these three categories. If sales or
stock availability fall in these categories, total revenue could be
affected significantly.

Business action

Keep strong stock availability for these categories.

Forecast demand carefully.

Monitor their performance regularly.

Review whether low-performing categories need improvement or less
investment.

### 2. More units sold does not always mean more revenue

Category             Revenue           Quantity

Clothing            ₹114.00M            103,558

Shoes                ₹66.55M            30,217

Technology           ₹57.86M            15,021

Cosmetics             ₹6.79M            45,465

Food & Beverage       ₹0.85M            44,277

What I found

Technology sold only about 15K units, but generated ₹57.86M.

Food & Beverage sold more than 44K units, but generated only
₹0.85M.

Simple business meaning

Selling more units does not always mean earning more revenue.

Some categories have much higher value per unit.

Business action

The business should look at both:

Quantity Sold + Revenue Generated

when deciding which products deserve more attention.

### 3. Female customers generate more revenue

Gender              Revenue       Revenue Share

Female             ₹150.21M          59.72%

Male               ₹101.30M          40.28%

What I found

Female customers generate almost 60% of total revenue.

They also generate more revenue than male customers across:

Cash

Credit Card

Debit Card

Why this matters

Female customers are the largest revenue-generating customer segment.

Business action

The business could:

Create targeted offers for female customers.

Study which products they buy most.

Create personalized recommendations.

Focus retention and loyalty campaigns on high-value customers.

### 4. Customers aged 36+ are the biggest revenue group

Age Group          Revenue

50+        ₹91.31M
36--50     ₹74.20M
26--35     ₹47.88M
18--25     ₹38.12M

What I found

Customers aged 36 and above generate about 66% of total revenue.

The 50+ group is the largest contributor, generating ₹91.31M.

Why this matters

Older customer groups are currently more valuable in terms of revenue.

Business action

The business could:

Create targeted offers for 36+ customers.

Build loyalty programs for high-value customers.

Study what products these customers prefer.

Use different marketing strategies for different age groups.

### 5. Two shopping malls generate around 40% of revenue

Shopping Mall                Revenue

Mall of Istanbul     ₹50.87M
Kanyon               ₹50.55M
Metrocity            ₹37.30M
Metropol AVM         ₹25.38M
Istinye Park         ₹24.62M

What I found

Mall of Istanbul and Kanyon are the two strongest locations.

Together they generate about ₹101.4M, or around 40% of total
revenue.

Why this matters

A large part of the business revenue comes from these two locations.

Business action

Keep sufficient stock in these malls.

Understand what makes these locations successful.

Compare their strategies with weaker locations.

Use successful practices where possible.

6. Clothing is the strongest category across major malls

The Mall × Category analysis shows that Clothing is the leading
revenue category across the major shopping malls.

Examples:

Mall of Istanbul

Clothing: ₹22.95M

Shoes: ₹13.47M

Technology: ₹11.83M

Kanyon

Clothing: ₹22.65M

Shoes: ₹13.38M

Technology: ₹11.94M

Metrocity

Clothing: ₹17.23M

Shoes: ₹9.52M

Technology: ₹8.61M

What I found

Clothing performs strongly across locations, not just in one mall.

Business action

The business should monitor Clothing demand by location and make sure
the right products are available in the right malls.

### 7. Cash is the most-used revenue-generating payment method

Payment Method          Revenue                Share

Cash                    ₹112.83M                ~45%
Credit Card             ₹88.08M                 ~35%
Debit Card              ₹50.60M                 ~20%

What I found

Cash generates the most revenue, followed by Credit Card and Debit Card.

Why this matters

Customers still show a strong preference for cash payments.

Business action

The business should continue supporting cash while testing small
incentives for digital payments, such as card offers or loyalty
benefits.

### 8. Revenue is strongest in January and weakest in November

Month                Revenue

January              ₹28.89M
February             ₹26.63M
March                ₹21.96M
April                ₹18.72M
May                  ₹19.72M
June                 ₹18.93M
July                 ₹20.38M
August               ₹19.28M
September            ₹18.80M
October              ₹20.55M
November             ₹18.21M
December             ₹19.46M

What I found

January has the highest revenue at ₹28.89M.

November has the lowest at ₹18.21M.

Revenue is about 37% lower in November than in January.

However, revenue does not continuously decline. There are several
months where revenue improves, such as May, July, October, and December.

Business action

The business should investigate why revenue is stronger in some months
and weaker in others.

Possible factors include:

Product demand

Promotions

Customer mix

Mall performance

Seasonal demand

### 9. Revenue is fairly similar across days of the week

Day                Revenue

Monday             ₹37.30M
Tuesday            ₹36.30M
Thursday           ₹35.74M
Friday             ₹35.73M
Sunday             ₹35.69M
Wednesday          ₹35.58M
Saturday           ₹35.18M

What I found

Monday has the highest revenue and Saturday has the lowest.

But the difference is relatively small.

Simple business meaning

Revenue is fairly stable across the week. The business does not appear
to depend heavily on one particular weekday.

Business action

Instead of focusing only on weekdays, the business should make decisions
using stronger factors such as:

Category + Customer + Location + Month

### 10. 2021 and 2022 revenue were stable

Year       Revenue

2021      ₹114.56M
2022      ₹115.44M
2023      ₹21.51M*

*2023 contains only January--March data.

What I found

Revenue increased only slightly from 2021 to 2022:

₹114.56M → ₹115.44M

That is approximately a 0.8% increase.

The 2023 figure should not be compared directly with full-year 2021
or 2022 because only three months of 2023 are available.

Important analyst point

For a fair comparison, compare:

Q1 2022 vs Q1 2023

rather than:

Full-year 2022 vs Q1 2023

This avoids making a wrong conclusion from incomplete data.


## 💡 Business Improvement Opportunities

Based on the analysis, I identified these main opportunities:

### 1. Protect the main revenue drivers

Clothing, Shoes, and Technology generate about 95% of revenue.

Action: Prioritize stock, demand forecasting, and performance
monitoring for these categories.

### 2. Focus on high-value customers

Customers aged 36+ generate about 66% of revenue.

Action: Use targeted loyalty and retention strategies for these
customers.

### 3. Strengthen top locations

Mall of Istanbul and Kanyon generate around 40% of revenue.

Action: Maintain strong stock and customer experience in these
locations and learn from their performance.

### 4. Use customer segmentation

Female customers generate about 60% of revenue.

Action: Create more targeted marketing based on gender, age, and
product preference.

### 5. Look beyond quantity

Some categories sell many units but generate little revenue, while
Technology generates high revenue with fewer units.

Action: Evaluate products using both volume and revenue.

### 6. Investigate monthly changes

January performs much better than November, but the monthly trend has
several ups and downs.

Action: Study promotions, seasonality, customer mix, product demand,
and mall performance to understand the changes.

## 📈 Excel Dashboard

The dashboard allows users to view:

Total Revenue

Average Order Value

Total Transactions

Revenue by Category

Revenue by Gender

Monthly Revenue Trend

Revenue by Payment Method

Revenue by Day of Week

Top 5 Shopping Malls by Revenue

Interactive Filters

Year

Gender

Age Group

These filters allow the user to drill down and see how the results
change for different customer segments and time periods.

🧠 Analysis Approach

I followed a simple business-analysis process:

Raw Data
   ↓
Data Preparation
   ↓
Pivot Tables
   ↓
KPIs & Charts
   ↓
Find Patterns
   ↓
Explain Why They Matter
   ↓
Business Recommendations

The main focus was to convert numbers into clear business insights and
actions.

## 🎯 Final Takeaways

The analysis shows that:

Clothing is the biggest revenue category.

Clothing, Shoes, and Technology generate about 95% of revenue.

Female customers generate about 60% of revenue.

Customers aged 36+ generate about 66% of revenue.

Mall of Istanbul and Kanyon generate around 40% of revenue
together.

Technology generates high revenue even with relatively low
quantity sold.

Cash is the largest payment method by revenue.

January is the strongest month and November is the weakest.

Revenue is fairly stable across weekdays.

2021 and 2022 revenue were almost stable.

2023 contains only Q1 data, so a full-year comparison is not
appropriate.

### 🚀 Project Outcome

This project demonstrates how Excel can be used for more than
reporting.

I used Excel to:

Analyze → Find Patterns → Understand Business Impact → Recommend
Actions

The final dashboard helps management understand:

Revenue → Customers → Products → Locations → Payment Behavior → Trends
→ Business Improvement


Built with Microsoft Excel | Retail Sales & Customer Analytics
