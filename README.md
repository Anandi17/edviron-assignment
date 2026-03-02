Data Analyst – Excel / Power BI Assignment
(Revenue, Commission & Settlement Analytics)
Business Context (Must Read Carefully)
You are given a transactional earnings file representing payments processed through Edviron’s platform.
There are three pricing layers involved in every transaction:
1. Edviron Buying Price
→ Rate at which Edviron buys payment processing (cost to Edviron)
2. Partner Pricing (ERP Pricing)
→ Rate at which Edviron sells payment processing to ERP partners
3. Merchant Pricing (School Pricing)
→ Rate at which ERP sells payment processing to schools
Revenue Definitions
• ERP Revenue
= Merchant Pricing – Partner Pricing
• Edviron Net Revenue
= Partner Pricing – Edviron Buying
• Edviron Gross Revenue
= ERP Revenue + Edviron Net Revenue
(Note: Payment Gateway settles the entire gross amount to Edviron, and Edviron later settles ERP’s share)
Your task is to analyze, compute, report, and visualize these revenues using Excel or Power BI.
Dataset Provided
You will receive:
• A raw Excel file containing transactional data with fields such as:
Order ID
Transaction Amount
Payment Method
Bank
Gateway
Student Name
Vendor Amount
Partner Pricing (Flat / %)
Merchant Pricing (Flat / %)
Edviron Buying (Flat / %)
Status (SUCCESS / FAILED / PENDING)
Capture Status
ERP Commission
Assume this is raw, unclean data.
Assignment Objectives
Part 1: Data Cleaning & Normalization (Excel / Power BI)
1. Clean the dataset:
• Handle missing values
• Standardize pricing formats (Flat vs Percentage)
• Ensure numeric consistency
2. Convert all pricing fields into absolute INR values per transaction, regardless of whether the input is Flat or Percentage.
3. Create helper columns/measures where required, but maintain clarity and auditability.
Part 2: Revenue & Commission Computation
For each transaction, compute:
ERP Revenue
Edviron Net Revenue
Edviron Gross Revenue
Gateway Fees (if inferable)
Net Settlement Amounts
Amount payable to ERP
Amount retained by Edviron
Clearly document assumptions wherever data is missing or implicit.
Part 3: Reports
1. Daily / Weekly / Monthly Revenue Summary
• Total Transaction Volume
• ERP Revenue
• Edviron Net Revenue
• Edviron Gross Revenue
• Unique Users
2. Partner (ERP-wise) Performance
• Transactions
• Revenue split (ERP vs Edviron)
• Average take rate
3. Gateway-wise & Payment Method Analysis
• Volume
• Revenue
• Success vs Failure rates
4. Pending vs Settled Exposure Report
• Capture Pending
• ERP payable outstanding
• Edviron receivable risk
Use Pivot Tables (Excel) or Visual Reports (Power BI) wherever appropriate.
Part 4: Interactive Dashboard (Core Evaluation)
Build an interactive dashboard using Excel or Power BI.
Dashboard must include:
Key Metrics (Top Tiles)
Total Transactions
Total GMV
ERP Revenue
Edviron Net Revenue
Edviron Gross Revenue
Pending Exposure
Unique Users
Frequency of payment of same user
Visuals (Charts)
Revenue split (Edviron vs ERP)
Time-based trend (Daily / Monthly)
Gateway-wise contribution
Payment method mix
Controls (Mandatory)
Date Range Selector
Partner (ERP) Filter
Gateway Filter
Payment Method Filter
All visuals and metrics should dynamically update using formulas, DAX, or data model logic — not manual filtering.
Part 5: Modeling Expectations
Use Excel formulas or DAX for:
• Dynamic filtering
• Metric recalculation
• Dashboard refresh logic
Model should be:
• Modular
• Commented (where applicable)
• Readable
• No hard-coded cell references or fixed-value logic in business calculations.
Deliverables
1. Excel File (.xlsx) or Power BI File (.pbix)
• Clean data
• Computation sheets / Data model
• Reports
• Dashboard
2. 1–2 page Explanation Note (PDF or Sheet)
• Revenue logic explanation
• Assumptions made
• Dashboard design rationale
Evaluation Criteria
Area
Weight
Financial logic accuracy
High
Excel/Power BI modeling & reports
High
Dashboard quality & usability
Very High
Dashboard clarity
High
Business thinking
High
Documentation
Medium

Bonus (Not Mandatory, But Strong Signal)
• Automated reconciliation logic
• Exception flagging (negative margins, pricing errors)
• Scenario toggles (Flat vs % stress test)
• Clean UX/UI polish
