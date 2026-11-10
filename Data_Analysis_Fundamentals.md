# Analyst Fundamentals – Study Notes

## 1. Introduction to Data Analysis

### What is Data Analysis?

Data Analysis is the process of examining, cleaning, transforming and interpreting data to discover useful information and support decision-making.

### Why is Data Analysis Important?

Organisations collect large amounts of data. Data analysis helps them:

- Understand what is happening.
- Identify problems.
- Discover patterns and trends.
- Measure performance.
- Make informed decisions.

### Example

A retail company notices that sales are decreasing.

An analyst examines sales data to understand:
- Which products have declining sales?
- Which regions are affected?
- When did sales start decreasing?
- What factors might explain the decline?

The analyst then presents findings and recommendations.

### Data Analysis Process

1. **Define the Problem:** Understand the question.
2. **Collect Data:** Gather relevant information.
3. **Clean Data:** Correct data quality issues.
4. **Explore Data:** Understand patterns and distributions.
5. **Analyse Data:** Apply appropriate analytical techniques.
6. **Visualise Results:** Create charts and dashboards.
7. **Communicate Insights:** Explain findings and recommendations.

---

## 2. Types of Data

### Qualitative Data

Describes characteristics or categories.

Examples:
- Gender
- Department
- Customer feedback
- Product category

### Quantitative Data

Represents numerical measurements or counts.

Examples:
- Salary
- Age
- Revenue
- Number of employees

### Discrete Data

Countable numerical values.

Example: Number of customers = 150.

### Continuous Data

Measured numerical values that can take values within a range.

Example: Temperature = 25.6°C.

### Structured Data

Organised in rows and columns.

Example: SQL database tables.

### Unstructured Data

Does not follow a fixed table structure.

Examples: Emails, images and documents.

**Remember:** Understanding data types helps determine which analytical methods are appropriate.

---

## 3. Data Collection

Data collection is the process of gathering information for analysis.

### Data Sources

- Relational databases
- Excel spreadsheets
- CSV files
- APIs
- Surveys
- Business applications
- Public datasets

### Primary Data

Data collected directly for a specific purpose.

Example: Conducting a customer satisfaction survey.

### Secondary Data

Data collected previously by another person or organisation.

Example: Using publicly available census data.

### Important Considerations

Before analysing data, check:

1. Is the source reliable?
2. Is the data relevant?
3. Is the data complete?
4. Is the data current enough?
5. Is the data collected and used legally and ethically?

---

## 4. Data Cleaning

### What is Data Cleaning?

Data cleaning is the process of identifying and correcting errors, inconsistencies and missing information in a dataset.

Poor-quality data can produce incorrect conclusions.

### Common Data Quality Problems

**1. Missing Values**

Example:

| Name | Age |
|---|---|
| John | 25 |
| Mary | Missing |

Possible solutions:
- Remove records when appropriate.
- Replace missing values using suitable methods.
- Investigate the source.
- Keep missing values when they have analytical meaning.

**2. Duplicate Records**

The same record appears multiple times.

Example: The same transaction was imported twice.

Solution: Identify duplicates using appropriate unique identifiers before removing them.

**3. Incorrect Data Types**

Example: A salary stored as text instead of a number.

Solution: Convert it to a numeric data type.

**4. Inconsistent Formatting**

Examples:
- NZ
- New Zealand
- new zealand

Solution: Standardise values.

**5. Outliers**

Values that are unusually different from other observations.

Example: Most salaries are between $50,000 and $100,000, but one is $900,000.

An outlier may be a valid observation or a data error. Investigate before removing it.

---

## 5. Exploratory Data Analysis (EDA)

### What is EDA?

Exploratory Data Analysis is the process of examining a dataset to understand its structure, characteristics, patterns and possible relationships.

EDA is usually performed before advanced statistical modelling.

### Common EDA Activities

- Examine dataset dimensions.
- Check column names and data types.
- Identify missing values.
- Calculate descriptive statistics.
- Examine distributions.
- Detect outliers.
- Compare groups.
- Explore relationships between variables.

### Example

A company has employee salary data.

An analyst might investigate:
- Average salary
- Median salary
- Highest and lowest salary
- Salary distribution
- Salary differences between departments

### Common EDA Visualisations

- Histograms
- Box plots
- Bar charts
- Scatter plots
- Line charts

---

## 6. Descriptive Statistics

Descriptive statistics summarise and describe data.

### Mean

The arithmetic average of values.

Formula:

`Mean = Sum of Values / Number of Values`

Example:

Values: 10, 20, 30

Mean = (10 + 20 + 30) / 3 = 20

### Median

The middle value after sorting the data.

Example:

10, 20, 30, 40, 50

Median = 30

For an even number of values, take the average of the two middle values.

### Mode

The most frequently occurring value.

Example:

10, 20, 20, 30, 40

Mode = 20

### Range

Difference between the maximum and minimum values.

`Range = Maximum - Minimum`

Example:

50 - 10 = 40

### Variance

Measures how spread out values are around the mean using squared deviations.

### Standard Deviation

Measures the spread of values around the mean in the original unit of measurement.

- Low standard deviation: Values are relatively close to the mean.
- High standard deviation: Values are more spread out.

### Percentile

A percentile describes the relative position of a value within a dataset.

Example:

A score at the 90th percentile is approximately higher than 90% of the scores.

---

## 7. Data Analysis Techniques

### Descriptive Analysis

Answers: **What happened?**

Example: Total sales last month were $100,000.

### Diagnostic Analysis

Answers: **Why did it happen?**

Example: Sales declined because a major product was unavailable.

This explanation should be supported by evidence.

### Predictive Analysis

Answers: **What might happen?**

Example: Forecasting next month's sales using historical data.

### Prescriptive Analysis

Answers: **What should we do?**

Example: Recommending inventory changes based on demand forecasts and costs.

---

## 8. Trend Analysis

### What is Trend Analysis?

Trend analysis examines how a variable changes over time.

It helps identify:
- Increasing trends
- Decreasing trends
- Stable patterns
- Seasonal patterns
- Unusual changes

### Example

| Year | Sales |
|---|---|
| 2023 | 100 |
| 2024 | 120 |
| 2025 | 150 |

Sales increased over the three years.

### Percentage Change

Formula:

`((New Value - Old Value) / Old Value) × 100`

Example:

`((150 - 120) / 120) × 100 = 25%`

Sales increased by 25% from 2024 to 2025.

### Percentage vs Percentage Points

Suppose attendance increases from 80% to 90%.

- Percentage-point increase = 10 percentage points.
- Relative percentage increase = 12.5%.

These are different measurements.

---

## 9. Correlation and Causation

### Correlation

Correlation describes the strength and direction of a relationship between two variables.

The Pearson correlation coefficient ranges from -1 to +1.

- +1: Perfect positive linear correlation.
- 0: No linear correlation.
- -1: Perfect negative linear correlation.

### Example

Advertising spending and sales may increase together.

This indicates a possible positive relationship.

### Causation

Causation means a change in one factor produces a change in another.

**Important:** Correlation does not prove causation.

Other variables may explain an observed relationship.

---

## 10. KPI Analysis

### What is a KPI?

KPI stands for Key Performance Indicator.

A KPI is a measurable indicator used to evaluate progress towards a specific objective.

### Examples

- Revenue growth
- Customer retention rate
- Employee turnover rate
- Order fulfilment time
- Customer satisfaction

### KPI vs Metric

**Metric:** Any quantitative measurement.

**KPI:** A metric specifically connected to an important objective.

### Example

Objective: Improve customer satisfaction.

KPI: Customer satisfaction score.

Target: 90%.

Actual: 85%.

Performance gap: 5 percentage points below target.

---

## 11. Data Visualisation

### What is Data Visualisation?

Data visualisation presents information through charts, graphs and maps to make patterns easier to understand.

### Common Charts

| Chart | Purpose |
|---|---|
| Bar Chart | Compare categories |
| Line Chart | Show changes over time |
| Histogram | Show numerical distributions |
| Scatter Plot | Examine relationships |
| Box Plot | Show spread and outliers |
| Map | Show geographical patterns |
| KPI Card | Display a key measurement |

### Good Visualisation Practices

1. Choose a suitable chart.
2. Use clear titles.
3. Label axes.
4. Avoid unnecessary visual elements.
5. Use consistent units.
6. Avoid misleading scales.
7. Highlight important findings.

---

## 12. SQL Fundamentals

### What is SQL?

SQL stands for Structured Query Language.

It is used to retrieve, manage and analyse data stored in relational databases.

### Important Commands

**SELECT:** Retrieve columns.

```sql
SELECT name, salary
FROM employees;
```

**WHERE:** Filter records.

```sql
SELECT *
FROM employees
WHERE salary > 60000;
```

**GROUP BY:** Group records for aggregation.

```sql
SELECT department, COUNT(*)
FROM employees
GROUP BY department;
```

**HAVING:** Filter aggregated groups.

```sql
SELECT department, COUNT(*)
FROM employees
GROUP BY department
HAVING COUNT(*) > 5;
```

**JOIN:** Combine related tables.

```sql
SELECT e.name, d.department_name
FROM employees e
INNER JOIN departments d
    ON e.department_id = d.department_id;
```

### Important SQL Topics to Learn

- Filtering
- Sorting
- Aggregation
- Joins
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- NULL handling

---

## 13. Excel Fundamentals

Excel is commonly used for data preparation, analysis and reporting.

### Important Functions

| Function | Purpose |
|---|---|
| SUM | Adds values |
| AVERAGE | Calculates the mean |
| COUNT | Counts numeric cells |
| COUNTIF | Counts cells meeting a condition |
| SUMIFS | Sums values using multiple conditions |
| IF | Applies conditional logic |
| XLOOKUP | Looks up related values |
| IFERROR | Handles formula errors |
| TRIM | Removes extra spaces |

### Pivot Tables

Pivot Tables summarise large datasets without writing complex formulas.

Example:

A sales dataset contains thousands of transactions.

A Pivot Table can calculate total sales by region or product category.

### Power Query

Power Query is used to import, clean and transform data through repeatable steps.

---

## 14. Power BI Fundamentals

Power BI is a business intelligence platform for data analysis and interactive reporting.

### Main Components

**Power Query**

Used for extracting, cleaning and transforming data.

**Data Modelling**

Defines relationships between tables.

**DAX**

Data Analysis Expressions is a formula language used to create measures and calculations.

**Visualisations**

Charts, tables, maps and KPI indicators.

### Star Schema

A common data modelling approach.

**Fact Table:** Stores measurable events or transactions.

Example: Sales transactions.

**Dimension Table:** Stores descriptive information.

Examples: Customers, products and dates.

### Example DAX

```dax
Total Sales = SUM(Sales[Amount])

Total Orders = COUNTROWS(Sales)
```

---

## 15. Business Analysis Fundamentals

Business Analysis focuses on understanding business needs and identifying suitable solutions.

### Requirements Gathering

Collecting information about what stakeholders need.

Methods include:
- Interviews
- Workshops
- Surveys
- Observation
- Document analysis

### Functional Requirements

Describe what a system must do.

Example: Users must be able to download reports.

### Non-Functional Requirements

Describe quality attributes or constraints.

Example: A report should load within 3 seconds under defined conditions.

### Gap Analysis

Compares the current situation with the desired future situation.

Example:

Current: Manual reporting.

Future: Automated reporting.

Gap: An automated reporting solution is needed.

### Process Mapping

Visual representation of a workflow.

- As-Is: Current process.
- To-Be: Proposed future process.

---

## 16. Data Quality

Data quality describes how suitable data is for its intended purpose.

### Main Dimensions

| Dimension | Explanation |
|---|---|
| Accuracy | Values correctly represent reality |
| Completeness | Required values are available |
| Consistency | Data agrees across systems |
| Validity | Data follows expected rules |
| Uniqueness | Records are not unintentionally duplicated |
| Timeliness | Data is sufficiently current |

### Example

A customer database contains duplicate records and missing contact details.

These issues can affect customer counts and reporting accuracy.

---

## 17. Data Interpretation

### What is Data Interpretation?

Data interpretation means explaining what analytical results indicate and how they relate to the original question.

### Difference Between Data, Information and Insight

**Data:** Raw observations.

Example: 100, 120, 150.

**Information:** Organised data with context.

Example: Sales increased from 100 to 150 units over three years.

**Insight:** A meaningful finding that supports further investigation or action.

Example: Sales growth is concentrated in one product category.

### Recommendation

A suggested action based on evidence.

Example: Investigate opportunities to expand the high-performing product category.

---

## 18. Analytical Report Writing

A good analytical report should explain the problem, methods, findings and recommendations.

### Basic Structure

1. Executive Summary
2. Objective
3. Data Sources
4. Methodology
5. Findings
6. Interpretation
7. Limitations
8. Recommendations
9. Conclusion

### Example

**Objective:** Understand declining sales.

**Finding:** Sales decreased by 15% in one region.

**Analysis:** The decline was concentrated in two product categories.

**Recommendation:** Investigate product availability, pricing and customer demand.

---

## 19. Data Privacy and Ethics

Analysts must handle information responsibly.

### Important Principles

- Use data for legitimate purposes.
- Protect personal information.
- Restrict access to authorised users.
- Avoid unnecessary collection of sensitive data.
- Identify possible bias.
- Explain uncertainty and limitations.
- Report findings accurately.

### Example

When analysing employee salaries, personal identifiers should not be disclosed unnecessarily.

---

## 20. Essential Concepts – Quick Revision

| Concept | Meaning |
|---|---|
| Data Cleaning | Correcting data quality problems |
| Data Validation | Checking data against defined rules |
| EDA | Exploring and understanding data |
| Mean | Arithmetic average |
| Median | Middle value |
| Standard Deviation | Measure of data spread |
| Correlation | Relationship between variables |
| Trend Analysis | Examining changes over time |
| KPI | Indicator measuring progress towards an objective |
| SQL | Language for relational databases |
| ETL | Extract, Transform, Load |
| DAX | Formula language used in Power BI |
| Star Schema | Fact and dimension table model |
| Gap Analysis | Comparing current and desired states |
| Stakeholder | Person or group affected by or influencing work |
| Data Visualisation | Presenting information graphically |
| Insight | Meaningful analytical finding |



## Summary

The purpose of analysis is to convert raw information into useful knowledge.

**Problem → Data → Analysis → Insights → Recommendations → Decisions**

A good Analyst understands the problem, selects appropriate methods, checks the reliability of the results and communicates findings clearly.
