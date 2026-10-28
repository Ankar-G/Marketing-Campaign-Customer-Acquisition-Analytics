# Marketing Campaign & Customer Acquisition Analytics

An end-to-end marketing analytics project focused on evaluating campaign performance, measuring customer acquisition efficiency, and identifying opportunities to improve marketing profitability through data-driven insights.

## 📌 Table of Contents

1. [Project Overview](#1-project-overview)
2. [Problem Statement](#2-problem-statement)
3. [Business Objectives](#3-business-objectives)
4. [Project Workflow](#4-project-workflow)
5. [Dataset and Data Model](#5-dataset-and-data-model)
6. [Data Cleaning and Preparation](#6-data-cleaning-and-preparation)
7. [Key Calculations and Metrics](#7-key-calculations-and-metrics)
8. [Dashboard Overview](#8-dashboard-overview)
9. [Individual Dashboard Analysis](#9-individual-dashboard-analysis)
10. [Key Project Insights](#10-key-project-insights)
11. [Business Value](#11-business-value)
12. [Business Questions Answered](#12-business-questions-answered)
13. [Technical Skills and Tools](#13-technical-skills-and-tools)
14. [Project Structure](#14-project-structure)
15. [Data Validation Notes](#15-data-validation-notes)
16. [Dashboard Preview](#16-dashboard-preview)
17. [Connect With Me](#17-connect-with-me)

---

## 1. Project Overview

Marketing Campaign & Customer Acquisition Analytics is a marketing analytics project designed to evaluate how effectively marketing investments generate leads, conversions, and attributed revenue.

The project examines marketing spend, campaign performance, acquisition channels, customer conversion behaviour, and customer acquisition costs to help identify areas where marketing resources can be used more efficiently.

The analysis focuses on key performance indicators such as Return on Advertising Spend (ROAS), Marketing ROI, Customer Acquisition Cost (CAC), Click-Through Rate (CTR), Conversion Rate, and Customer Lifetime Value (CLV), where applicable.

The objective is to transform marketing performance data into actionable insights that support better budget allocation, improved campaign efficiency, and sustainable customer acquisition.

### Project Highlights

- Marketing spend and attributed revenue analysis
- Campaign and acquisition channel performance evaluation
- Customer acquisition cost and conversion efficiency monitoring
- Marketing ROI and ROAS measurement
- Lead generation and conversion funnel analysis
- Customer value and acquisition efficiency assessment
- Interactive dashboard-based performance reporting

## 2. Problem Statement

Marketing teams invest in multiple channels and campaigns to attract potential customers and generate revenue. However, high marketing expenditure does not necessarily translate into profitable customer acquisition.

Without a structured analytics solution, businesses may struggle to determine:

- Which marketing channels generate the strongest returns?
- Are marketing campaigns generating enough revenue to justify their costs?
- How efficiently are leads converting into customers?
- Which channels have the highest customer acquisition costs?
- Where are potential customers dropping out of the conversion funnel?
- How can marketing budgets be allocated more effectively?
- Are acquired customers generating sufficient value relative to acquisition costs?

This project addresses these challenges by organizing marketing performance metrics into an analytical reporting solution that helps evaluate acquisition efficiency, campaign effectiveness, and marketing profitability.

## 3. Business Objectives

| Objective | Description |
|---|---|
| Campaign Performance Analysis | Evaluate campaign expenditure, conversions, and attributed revenue. |
| Channel Performance Analysis | Compare acquisition channels based on spend, traffic, conversions, and returns. |
| Customer Acquisition Analysis | Measure CAC and identify opportunities to acquire customers more efficiently. |
| Conversion Funnel Analysis | Evaluate the movement from impressions and clicks to leads and conversions. |
| Marketing Profitability | Assess marketing performance using ROI and ROAS. |
| Customer Value Analysis | Examine customer value and the CLV-to-CAC relationship where data is available. |
| Budget Optimization | Identify opportunities to improve marketing investment allocation. |
| Performance Monitoring | Track marketing trends and identify underperforming areas. |

## 4. Project Workflow

The project follows a marketing analytics workflow that moves from data preparation to performance measurement and business recommendations.

```text
Marketing Data
      ↓
Data Validation and Preparation
      ↓
Data Transformation and Modeling
      ↓
Marketing KPI Calculations
      ↓
Campaign and Channel Analysis
      ↓
Customer Acquisition Analysis
      ↓
Dashboard Development
      ↓
Business Insights
      ↓
Marketing Recommendations
```

1. **Data Collection** — Gather the marketing and acquisition data required for analysis. `[PLACEHOLDER: confirm source files and data sources]`
2. **Data Cleaning and Preparation** — Prepare the data for consistent analysis. `[PLACEHOLDER: confirm completed cleaning steps]`
3. **Data Modeling** — Organize the relevant marketing, campaign, and customer information. `[PLACEHOLDER: confirm actual tables and relationships]`
4. **KPI Development** — Calculate marketing expenditure, attributed revenue, conversions, CAC, ROI, ROAS, and other relevant measures.
5. **Dashboard Development** — Present campaign and acquisition performance through dashboard visualizations.
6. **Insight Generation** — Identify performance differences, trends, and opportunities for improvement.
7. **Business Recommendations** — Translate analytical findings into potential marketing optimization actions.

## 5. Dataset and Data Model

The project analyzes marketing performance across campaign and acquisition dimensions.

The exact dataset schema, record count, and table relationships must be confirmed against the actual source files. The following table describes the information required for the analysis rather than asserting that every field exists in the dataset.

| Data Category | Relevant Fields |
|---|---|
| Campaign Information | Campaign ID, Campaign Name, Campaign Type |
| Marketing Channels | Channel ID, Channel Name |
| Marketing Investment | Marketing Spend, Campaign Cost |
| Traffic Performance | Impressions, Clicks, CTR |
| Lead Generation | Leads, Lead Conversion Metrics |
| Conversion Performance | Conversions, Conversion Rate |
| Revenue Performance | Attributed Revenue |
| Customer Acquisition | Acquired Customers, CAC |
| Customer Value | Customer Lifetime Value, CLV-to-CAC |
| Time Dimensions | Campaign Date, Month, Quarter `[confirm available fields]` |

### Data Model

The project requires consistent relationships between marketing activities, campaigns, acquisition channels, and conversion outcomes to support meaningful comparisons.

`[PLACEHOLDER: Add the actual table names, primary keys, foreign keys, and relationships after confirming the dataset or data model.]`

## 6. Data Cleaning and Preparation

Reliable marketing analysis depends on consistent and accurate source data. The preparation process should address the following areas where applicable:

- Check for duplicate campaign or transaction records.
- Review missing values in important fields such as spend, clicks, conversions, and revenue.
- Standardize campaign names and marketing channel categories.
- Validate numerical data types and date fields.
- Check for negative or implausible values in spend, impressions, clicks, conversions, and revenue.
- Confirm that campaign and channel identifiers map correctly across related tables.
- Ensure that aggregated metrics use consistent filters and reporting periods.
- Validate that conversion and customer counts use clearly defined denominators.

**Implementation note:** These are recommended validation checks. The exact checks performed and any transformations applied should be confirmed against the actual project files before being documented as completed work.

## 7. Key Calculations and Metrics

The following metrics support marketing performance evaluation. Formulas should be aligned with the definitions used in the actual dashboard and source data.

| Metric | Formula | Business Purpose |
|---|---|---|
| Total Marketing Spend | Sum of marketing expenditure | Measures total marketing investment. |
| Attributed Revenue | Sum of revenue attributed to marketing activity | Measures revenue credited to campaigns or channels. |
| ROAS | Attributed Revenue ÷ Marketing Spend | Measures attributed revenue generated per unit of marketing spend. |
| Marketing ROI | (Attributed Revenue − Marketing Spend) ÷ Marketing Spend × 100 | Measures return after subtracting marketing spend, subject to the project's ROI definition. |
| Total Conversions | Sum of conversions | Measures conversion volume. |
| Cost per Conversion | Marketing Spend ÷ Conversions | Measures the average cost of generating a conversion. |
| CAC | Acquisition Spend ÷ Acquired Customers | Measures the average cost of acquiring a customer. |
| CTR | Clicks ÷ Impressions × 100 | Measures the percentage of impressions that generate clicks. |
| Conversion Rate | Conversions ÷ Relevant Starting Population × 100 | Measures the percentage progressing to the defined conversion event. |
| Historical Revenue per Customer | Attributed or historical revenue ÷ relevant customer count | Measures average revenue per customer, depending on the project definition. |
| CLV-to-CAC Ratio | Customer Lifetime Value ÷ CAC | Compares customer value with acquisition cost. |

### Important Metric Definitions

- **ROAS and ROI are different:** ROAS measures attributed revenue relative to advertising spend, while ROI generally accounts for the investment cost being evaluated.
- **Revenue is not necessarily profit:** A positive revenue-based ROI calculation does not establish business profitability unless the relevant costs are included.
- **CAC requires a customer count:** Conversions should not automatically be treated as acquired customers unless the dataset defines them as equivalent.
- **Conversion Rate requires a defined denominator:** Lead-to-customer conversion, click-to-conversion, and impression-to-conversion rates are different measures.
- **CLV must have a consistent definition:** Historical revenue per customer should not be described as predictive lifetime value unless a predictive method was implemented.

## 8. Dashboard Overview

The project includes marketing performance analysis covering investment, revenue, acquisition efficiency, and conversion behaviour.

The metrics recorded from the project details available are summarized below. Dashboard titles and the exact placement of each KPI should be confirmed against the original screenshots.

| Dashboard Area | Analytical Focus | Relevant Measures |
|---|---|---|
| Marketing Campaign Performance | Evaluate campaign investment and outcomes | Marketing Spend, Attributed Revenue, ROAS, ROI |
| Customer Acquisition Performance | Assess lead and customer acquisition efficiency | Leads, Conversions, CAC, Cost per Conversion |
| Channel and Funnel Analysis | Understand traffic, channel performance, and conversion efficiency | Impressions, Clicks, CTR, Conversion Rate |
| Customer Value Analysis | Compare customer value with acquisition costs | Historical Revenue per Customer, CLV-to-CAC |

`[PLACEHOLDER: Replace these analytical areas with the exact dashboard page titles shown in the screenshots.]`

## 9. Individual Dashboard Analysis

### Dashboard 1 — Marketing Campaign Performance

**Purpose:** Evaluate marketing investment against attributed revenue and conversion outcomes, helping identify whether marketing expenditure is generating measurable returns.

#### KPI Summary

| KPI | Displayed Value |
|---|---:|
| Total Marketing Spend | 3,283,068.24 |
| Attributed Revenue | 4,237,390.62 |
| ROAS | 1.29 |
| Marketing ROI | 122.80% |
| Conversions | 2,050 |

#### Main Visuals

The following visual topics were documented in the available project notes. Confirm the exact chart titles and types against the dashboard screenshot.

| Visualization | Analytical Purpose |
|---|---|
| Marketing Spend vs. Attributed Revenue | Compare marketing investment with revenue attributed to campaigns. |
| Conversions Trend | Track conversion performance over time. |
| Spend vs. Conversions by Campaign | Compare campaign investment and conversion volume. |
| CAC by Channel | Identify differences in customer acquisition costs across channels. |
| Acquisition Trend | Monitor changes in acquisition performance over time. |

#### Key Insights

1. **Marketing expenditure is substantial:** Total marketing spend is approximately 3.28 million, making efficient budget allocation an important business priority.
2. **Attributed revenue exceeds marketing spend:** Attributed revenue is approximately 4.24 million, or around 1.29 times the reported spend.
3. **The reported ROAS is 1.29:** This indicates approximately 1.29 units of attributed revenue per unit of marketing spend, assuming the dashboard uses the standard ROAS definition.
4. **The reported Marketing ROI requires definition validation:** The displayed ROI of 122.80% does not match the conventional revenue-based ROI calculation using the displayed spend and attributed revenue. See the Data Validation Notes section.
5. **The project records 2,050 conversions:** Campaign-level comparisons are needed to determine which campaigns deliver these conversions most efficiently.

#### Business Recommendations

- Compare campaign-level ROAS and acquisition costs before reallocating budget.
- Investigate campaigns with high spend but relatively low conversion output.
- Review the attribution model and ROI calculation before making investment decisions.
- Monitor campaign results over consistent reporting periods to avoid misleading comparisons.
- Prioritize campaigns based on business outcomes rather than conversion volume alone.

#### Business Questions Answered

- How much was spent on marketing?
- How much revenue was attributed to marketing?
- What ROAS and ROI are reported?
- How many conversions were recorded?
- Which campaigns require further performance evaluation?

### Dashboard 2 — Customer Acquisition and Conversion Funnel

**Purpose:** Evaluate how marketing activity translates into clicks, leads, and conversions, and identify potential areas of acquisition inefficiency.

#### KPI Summary

| KPI | Displayed Value |
|---|---:|
| Leads | 17,416 |
| Conversions | 2,050 |
| Conversion Rate | 11.77% |
| Customer Acquisition Cost (CAC) | 1,601.50 |
| Cost per Conversion | 188.51 |
| Impressions | 18,648,225 |
| Clicks | 270,703 |
| CTR | 1.45% |

#### Main Visuals

| Visualization | Analytical Purpose |
|---|---|
| Conversion Funnel | Review progression through marketing funnel stages. |
| CAC by Channel | Compare the reported cost of customer acquisition across channels. |
| Acquisition Trend | Examine changes in acquisition performance over time. |
| Channel or Campaign Comparison | Identify differences in traffic and acquisition results where shown. |

`[PLACEHOLDER: Confirm the exact chart titles, types, filters, and channel-level values from the screenshots.]`

#### Key Insights

1. **The campaign data records 18.65 million impressions and approximately 270.7 thousand clicks.** These figures provide the basis for assessing traffic generation.
2. **The reported CTR is 1.45%.** This indicates that the reported click volume is relatively small compared with total impressions.
3. **There are 17,416 leads and 2,050 conversions.** The relationship between these counts is important for evaluating lead quality and conversion performance.
4. **The reported CAC is 1,601.50.** This metric should be interpreted using the actual acquisition-spend and acquired-customer definitions.
5. **The reported cost per conversion is 188.51.** It should not be assumed to represent customer acquisition cost because a conversion may be a lead or another intermediate action.

#### Business Recommendations

- Review conversion rates at each funnel stage to identify where prospects are dropping off.
- Evaluate landing pages, targeting, and messaging if click-through performance is below internal campaign targets.
- Compare lead quality across channels instead of optimizing solely for lead volume.
- Validate the definition of CAC and distinguish it from cost per conversion.
- Monitor funnel metrics over time to determine whether acquisition improvements translate into more customers.

#### Business Questions Answered

- How many impressions, clicks, leads, and conversions were recorded?
- What CTR and conversion rate are reported?
- What are the reported CAC and cost per conversion?
- Where should the acquisition funnel be investigated for potential inefficiencies?

### Dashboard 3 — Channel, Campaign, and Customer Value Analysis

**Purpose:** Compare marketing performance across channels and customer groups, and evaluate whether acquisition activity is generating sufficient customer value.

#### KPI Summary

| KPI | Displayed Value |
|---|---:|
| Historical Revenue per Customer | 3,568.10 |
| CLV-to-CAC Ratio | 2.2 |

`[PLACEHOLDER: Add the remaining KPI cards and exact values shown on this dashboard, if applicable.]`

#### Main Visuals

| Visualization | Analytical Purpose |
|---|---|
| Customer Segment Distribution | Understand how customers are distributed across segments. |
| Channel Performance Comparison | Compare acquisition efficiency across available marketing channels. |
| Campaign Performance Comparison | Evaluate campaign-level differences in acquisition and returns. |
| Customer Value Analysis | Assess historical customer value relative to acquisition cost, where available. |

`[PLACEHOLDER: Confirm the exact dashboard title and visible chart names, categories, and values from the screenshots.]`

#### Key Insights

1. **Historical revenue per customer is reported as 3,568.10.** This provides an average historical revenue benchmark under the project's customer-value definition.
2. **The reported CLV-to-CAC ratio is 2.2.** If CLV and CAC are defined consistently, this indicates customer value is 2.2 times acquisition cost.
3. **Channel-level comparisons are needed to distinguish acquisition volume from acquisition quality.** A channel that brings in more customers may not necessarily deliver the best customer value.
4. **Customer segment analysis can help guide campaign targeting.** Segment-level performance should be compared using actual counts, revenue, and acquisition costs rather than assumptions.

#### Business Recommendations

- Compare customer acquisition costs and customer value by channel before increasing investment.
- Investigate whether high-volume channels also produce customers with strong historical value.
- Use customer segment findings to refine targeting and campaign messaging.
- Treat historical revenue per customer separately from predictive customer lifetime value.
- Confirm that CLV and CAC use consistent customer populations and reporting periods before relying on their ratio.

#### Business Questions Answered

- What is the reported historical revenue per customer?
- What CLV-to-CAC ratio is reported?
- How can channel performance be evaluated beyond conversion volume?
- Which customer segments may warrant further analysis?

## 10. Key Project Insights

The available project metrics support the following preliminary observations:

- **Marketing investment and attributed revenue:** The project reports marketing spend of 3,283,068.24 and attributed revenue of 4,237,390.62.
- **Reported ROAS:** The reported value is 1.29, subject to confirmation of the metric definition and aggregation method.
- **Conversion volume:** The project records 17,416 leads and 2,050 conversions.
- **Traffic performance:** The available metrics include 18,648,225 impressions, 270,703 clicks, and a reported CTR of 1.45%.
- **Acquisition efficiency:** The reported CAC is 1,601.50, while cost per conversion is 188.51. These metrics should be kept distinct.
- **Customer value:** The reported historical revenue per customer is 3,568.10, with a CLV-to-CAC ratio of 2.2. Both require consistent underlying definitions.
- **Metric validation is important:** The displayed Marketing ROI does not reconcile with the conventional revenue-based calculation using the supplied total spend and attributed revenue.

These are preliminary findings based on the metrics available in the project notes. Channel rankings, campaign winners, underperforming segments, and time-based trends should be added only after checking the relevant chart values.

## 11. Business Value

This project demonstrates how marketing analytics can support practical decisions across campaign management and customer acquisition.

- **Marketing budget optimization:** Compare investment and attributed revenue to support more informed budget allocation.
- **Campaign performance monitoring:** Evaluate campaigns using consistent performance indicators.
- **Acquisition cost control:** Track CAC and cost per conversion to identify potential efficiency improvements.
- **Funnel optimization:** Monitor traffic, leads, and conversions to identify stages requiring investigation.
- **Customer value assessment:** Compare acquisition costs with customer value where suitable data is available.
- **Data-driven decision-making:** Provide stakeholders with structured performance reporting rather than relying solely on isolated campaign metrics.
- **Performance transparency:** Establish a common set of metrics for comparing marketing activities.

The project is intended to demonstrate the analytical workflow used to turn marketing data into actionable business reporting.

## 12. Business Questions Answered

1. How much has been spent on marketing?
2. How much revenue has been attributed to marketing activities?
3. What ROAS and Marketing ROI are reported?
4. How many impressions, clicks, leads, and conversions were generated?
5. What is the reported click-through rate?
6. What is the reported conversion rate?
7. What are the customer acquisition cost and cost per conversion?
8. How can campaign performance be compared across available channels?
9. Which funnel stages should be examined for potential conversion losses?
10. What historical revenue per customer is reported?
11. What CLV-to-CAC ratio is reported?
12. Which additional data validations are required before making budget decisions?

## 13. Technical Skills and Tools

| Tool / Skill | Purpose |
|---|---|
| SQL | Data extraction, transformation, and analysis, where implemented. |
| Microsoft Excel | Data review, preparation, and supporting calculations, where implemented. |
| Power BI | Interactive reporting and dashboard development, where implemented. |
| DAX | Measure development for dashboard KPIs, where implemented. |
| Data Cleaning | Preparation and consistency checks for marketing data. |
| Marketing Analytics | Campaign, channel, funnel, and acquisition performance analysis. |
| KPI Development | Calculation and interpretation of marketing performance indicators. |
| Data Visualization | Presenting trends, comparisons, and performance measures. |
| Business Analysis | Translating analytical findings into potential business actions. |

`[PLACEHOLDER: Confirm the exact tools used in the completed project and remove any tools or techniques that were not implemented.]`

## 14. Project Structure

The following is a proposed repository structure. Update the folder and filenames to match the actual project files.

```text
marketing-campaign-customer-acquisition-analytics/
│
├── Data/
│   └── [PLACEHOLDER: source dataset filename]
│
├── SQL/
│   └── [PLACEHOLDER: SQL script filenames, if applicable]
│
├── Excel/
│   └── [PLACEHOLDER: Excel workbook filename, if applicable]
│
├── PowerBI/
│   └── [PLACEHOLDER: Power BI file, if applicable]
│
├── images/
│   ├── dashboard_1_campaign_performance.png
│   ├── dashboard_2_customer_acquisition.png
│   └── dashboard_3_customer_value.png
│
└── README.md
```

**Note:** The filenames above are proposed examples. Replace them with the actual repository paths and dashboard filenames before publishing.

## 15. Data Validation Notes

Metric validation is essential because marketing dashboards can display values that do not reconcile when formulas, filters, or aggregation methods differ.

### Validation 1 — ROAS

Using the available values:

- Attributed Revenue = 4,237,390.62
- Marketing Spend = 3,283,068.24

The conventional calculation is:

`ROAS = Attributed Revenue ÷ Marketing Spend`

The resulting ROAS is approximately **1.29**, which is consistent with the reported value when rounded to two decimal places.

### Validation 2 — Marketing ROI

Using the conventional revenue-based formula:

`Marketing ROI = (Attributed Revenue − Marketing Spend) ÷ Marketing Spend × 100`

The result is approximately **29.06%**, not the reported **122.80%**.

This discrepancy requires investigation. Possible explanations include a different ROI definition, a different revenue or cost measure, or inconsistent aggregation or filters. These are possibilities, not confirmed causes.

### Validation 3 — CTR

Using the available traffic metrics:

- Impressions = 18,648,225
- Clicks = 270,703

`CTR = Clicks ÷ Impressions × 100`

The result is approximately **1.45%**, consistent with the reported CTR after rounding.

### Validation 4 — Conversion Rate

Using the available leads and conversions:

- Leads = 17,416
- Conversions = 2,050

Conversions divided by leads is approximately **11.77%**.

This reconciles with the reported conversion rate **if** the dashboard defines conversion rate as conversions divided by leads. Confirm that this is the actual definition used.

### Validation 5 — CAC and Cost per Conversion

The reported values are:

- CAC = 1,601.50
- Cost per Conversion = 188.51

These values cannot be fully verified without the exact acquisition-spend measure, acquired-customer count, conversion definition, and aggregation logic.

### Validation 6 — CLV-to-CAC

The reported CLV-to-CAC ratio is 2.2, and historical revenue per customer is 3,568.10. These figures should not be assumed to reconcile without confirming the precise CLV measure, CAC denominator, and calculation context.

### Validation Summary

| Metric | Status | Notes |
|---|---|---|
| ROAS | Reconciles approximately | Matches the conventional calculation using reported attributed revenue and marketing spend. |
| Marketing ROI | Requires confirmation | Reported value does not match the conventional calculation using the same figures. |
| CTR | Reconciles approximately | Clicks divided by impressions is approximately 1.45%. |
| Conversion Rate | Conditionally reconciles | Matches conversions divided by leads; confirm the dashboard definition. |
| CAC | Requires confirmation | Underlying acquisition-spend and acquired-customer values are unavailable here. |
| Cost per Conversion | Requires confirmation | Underlying spend and conversion definition are unavailable here. |
| CLV-to-CAC | Requires confirmation | Underlying CLV and CAC calculation details are unavailable here. |

## 16. Dashboard Preview

Save the dashboard screenshots in an `images/` folder in the repository root. The following filenames are proposed and should be changed to match the actual dashboard titles and screenshot files.

### Marketing Campaign Performance

![Marketing Campaign Performance Dashboard](https://github.com/Ankar-G/Marketing-Campaign-Customer-Acquisition-Analytics/blob/main/Dashboards%20Screenshots/Dashboard%201.png)

### Customer Acquisition and Conversion Funnel

![Customer Acquisition and Conversion Funnel Dashboard](https://github.com/Ankar-G/Marketing-Campaign-Customer-Acquisition-Analytics/blob/main/Dashboards%20Screenshots/Dashboard%202.png)

### Channel, Campaign, and Customer Value Analysis

![Channel, Campaign, and Customer Value Analysis Dashboard](https://github.com/Ankar-G/Marketing-Campaign-Customer-Acquisition-Analytics/blob/main/Dashboards%20Screenshots/Dashboard%203.png)

### GitHub Image Setup

1. Create an `images/` folder in the repository root.
2. Save each dashboard screenshot in that folder.
3. Rename the files to match the paths used in this section, or update the Markdown paths.
4. Commit and push the screenshots along with `README.md`.
5. Open the README on GitHub and confirm that all images render correctly.

If the project contains more or fewer dashboards, add or remove the relevant preview subsections.

## 17. Connect With Me

**Ankar Goswami**

- **LinkedIn:** [linkedin.com/in/ankar-goswami-23a196245](https://www.linkedin.com/in/ankar-goswami-23a196245/)
- **GitHub:** [github.com/Ankar-G](https://github.com/Ankar-G)
- **Email:** [goswamijit99@gmail.com](mailto:goswamijit99@gmail.com)

