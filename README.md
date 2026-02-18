📊 Cloud Operations Data Quality Audit & Performance Analysis
📌 Project Overview

This project presents a structured data quality audit and analytical assessment of a cloud operations dataset containing 5,000 project records.

The objective was to:

Ensure dataset reliability through systematic validation

Analyze operational and financial performance metrics

Identify correlations and performance trends

Generate actionable business insights

This project simulates a real-world analytics task focused on governance, transparency, and performance optimization.

🎯 Key Objectives

Perform a comprehensive Data Quality Audit

Compute Descriptive Statistics for key financial and operational metrics

Conduct Correlation Analysis

Build meaningful data visualizations

Provide business-focused recommendations

🔎 Data Quality Audit

The dataset was validated using structured checks:

✅ Duplicate Records → 0 detected

⚠ Fully Empty Columns → 9

⚠ Partially Missing Columns → 3

✅ Negative Values → None detected

✅ Reversed Start/End Dates → None detected

⚠ Projects Over Budget → 509 (~10%)

Validation Methods Used

COUNTIF() → Duplicate detection

COUNTBLANK() → Missing values

IF(Start_Date > End_Date) → Date validation

IF(Value < 0) → Negative value checks

Budget Utilization = Budget_Consumed / Budget_Allocated

Additionally:

Date fields were corrected to proper date format

Financial columns were standardized to consistent currency formatting

📈 Descriptive Statistics (Highlights)
Metric	Key Insight
Budget Utilization	Avg 81%, Max 119%
Projects Over Budget	~10%
Resource Utilization	Avg 70%
Tagging Completeness	~90%

Most projects operate within budget, but a subset exceeds allocation, indicating governance improvement opportunities.

🔗 Correlation Analysis
Metric Pair	Correlation	Interpretation
Budget Allocated vs Budget Consumed	0.64	Moderate Positive
Budget Consumed vs Utilization	0.30	Weak Positive
Usage Cost vs Resource Utilization	-0.10	Very Weak Negative
Tagging Completeness vs Utilization	0.02	No Meaningful Relationship

Key Insight:
Spending levels moderately align with allocated budgets, but higher costs do not necessarily lead to better operational efficiency.

📊 Visualizations Included

Scatter Plot: Budget Allocated vs Budget Consumed

Histogram: Budget Utilization Distribution

Boxplot: Resource Utilization Spread

Scatter Plot: Usage Cost vs Resource Utilization

These visual insights highlight performance clustering, outliers, and inefficiencies.

💡 Business Recommendations

Implement early budget alerts at 85–90% utilization

Enforce mandatory metadata fields (Environment, Department, etc.)

Improve tagging governance for better segmentation

Introduce automated monitoring dashboards

🛠 Tools Used

Microsoft Excel

Data Validation

Pivot Tables

Statistical Functions

Correlation (CORREL)

Conditional Formatting

Dashboard Visualization

🚀 What This Project Demonstrates

Strong data validation practices

Analytical thinking and statistical interpretation

Dashboard design and visualization skills

Business-focused insight generation

Governance and performance awareness
