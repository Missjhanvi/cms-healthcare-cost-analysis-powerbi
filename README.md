📊CMS Healthcare Cost Analysis Dashboard
Power BI | DAX | Data Modeling | Business Intelligence

📌 Project Overview
This project analyzes the CMS Medicare Inpatient Hospital Dataset (2023) to evaluate hospital pricing behavior, Medicare reimbursement patterns, and healthcare cost variation across states and medical procedures (DRGs).
The objective was to design an interactive Power BI dashboard that delivers executive-level insights into hospital charge trends, Medicare reimbursement comparison, procedure-level cost concentration, state-level cost variation, and hospital efficiency analysis.

🏗 Data Modeling Approach
Implemented a Star Schema data model for optimized reporting and scalability.
Fact Table: fact_inpatient
• Total Discharges
• Avg Covered Charges
• Avg Total Payment
• Avg Medicare Payment

Dimension Tables
dim_hospital
• Provider ID
• Provider Name
• City
• State
• RUCA Classification

dim_drg
• DRG Code
• DRG Description

📈Key DAX Measures
• Total Discharges (Sum)
• Average Covered Charges
• Average Medicare Payment
• Payment Gap
• Cost to Medicare Ratio
• Medicare Coverage %

📊Dashboard Features
• Executive KPI Section
• Top 10 Most Expensive DRGs
• Payment Gap Analysis
• State-Level Cost Comparison
• Hospital Efficiency Scatter Plot
• Interactive Slicers

💡Business Insights
• Significant pricing variation exists across states.
• Certain DRGs consistently show high payment gaps.
• Medicare reimbursement does not scale proportionally with hospital charges.
• High-volume hospitals show clustered pricing behavior.

🛠Tools & Technologies Used
• Power BI Desktop
• DAX (Data Analysis Expressions)
• Star Schema Data Modeling
• Data Cleaning & Transformation
• KPI Design
• Interactive Dashboard Development
