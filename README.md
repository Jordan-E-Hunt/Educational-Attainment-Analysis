###[REPORT] Between High School and College: The Unspoken Way Side

##December 2025

##Jordan Hunt

##Python (Pandas, Matplotlib, Seaborn), Git, Google Colab

#Executive Summary
This project investigates the systemic, financial, and institutional barriers preventing minority students from successfully matriculating into higher levels of education. By comparing 2012 and 2022 Census data alongside education statistics from the Department of Education, this study identifies a multifaceted "enrollment gap" driven by high-school climate, parental educational attainment, and legislative funding shifts.

---

#Technical Methodology & Data Integrity
To ensure a robust analysis for this portfolio, a multi-stage data pipeline was developed:
• Data Ingestion: Aggregated four distinct datasets from the U.S. Census Bureau and the National Center for Education Statistics (NCES).
• Defensive Programming: Implemented automated sanitization scripts in Python to handle non-printable ASCII characters and "invisible" formatting errors in binary.xlsx files.
• Validation: Performed schema validation to ensure poverty percentages and aid-receipt ratios maintained mathematical integrity across racial categories.

#Core Analysis & Findings
A. The Institutional Support Gap
Utilizing the "Potholes on the Road to College" framework, the data suggests that a "college-going climate," where teachers set high expectations, is the strongest indicator of success. However, disadvantaged schools often promote "expedited adulthood," prioritizing immediate economic self-sufficiency over long-term academic training.
B. Financial & Systemic Disparities
• Loan Dependency: 48% of Black students received federal student loans, which is 13% higher than the national average (35%).
• Poverty Correlation: The data visualizes a stark correlation between adult education levels and household poverty percentages from 2012 to 2022, highlighting that parental education remains the single strongest correlate of a child's school success.
• Legislative Impact: Analysis of HR 471 (2011) and S-117 (2015) reveals a trend of defunding DoE resources for disadvantaged groups, creating a systemic barrier to entry.

#Systems Integrity & Security Statement
In alignment with Senior CS standards, this project treats data as a critical system component:
Viruses: Modify programs to include virus, secret execution, OS and hardware specific (dormant, propagation, triggering, execution) components: infection mechanism – replicator, trigger – payload activation, payload – purpose (malicious, benign).
By applying a sanitization layer to the Excel-based data pipeline, we mitigated the risk of binary-level infection mechanisms (such as malicious macros). This ensures the analytical payload—the generated charts and insights—is produced in a secure environment, protecting the OS and hardware integrity of any system deploying this repository.

#Conclusion & Future Work
The gap in higher education enrollment is not merely a financial issue; it is a systemic failure of support structures surrounding high school students. Future iterations of this project could involve training a predictive model to identify "at-risk" enrollment paths based on high school resource indicators.
