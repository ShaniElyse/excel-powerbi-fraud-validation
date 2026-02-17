# excel-powerbi-fraud-validation
Excel and Power BI project focused on data validation, anomaly detection, and fraud/risk analysis. Includes Excel-based sanity checks, exception flagging, and reconciliation workflows. Documentation, dashboards, and investigative findings will be added.
Problem											
• Reporting pipelines fail when source data has duplicates, invalid dates, negative values, or inconsistent logic.											
• Goal: validate HR/payroll/system data and a fraud transaction dataset before building dashboards and investigation views.											
											
Data											
• Raw_Data: HR/payroll/system fields with intentional quality issues (duplicates, negative values, invalid dates, risk signals).											
• Fraud_Only_Data: transactions + login indicators (velocity, country mismatch, risky merchants, chargebacks).											
											
Approach											
1) Built Excel validation flags (duplicates, invalid dates, negative values, overtime logic, high login attempts, foreign signals).											
2) Created control totals and pivot-based sanity checks for reconciliation.											
3) Loaded data into Power BI, enforced data types, and built matching DAX measures.											
4) Reconciled Excel and Power BI counts/totals; documented mismatches and fixes.											
											
Results											
• Identified and documented data quality issues before dashboarding.											
• Produced validated BI views and an investigation-ready exception table.											
• Built a repeatable validation checklist for future refreshes.											
											
Tools											
• Excel (formulas, pivots, conditional formatting)											
• Power BI (Power Query, DAX, model validation)											
											
What I’d Improve Next											
• Automate checks in Power Query / SQL											
• Add risk scoring and alert thresholds											
• Expand to log sources (authentication/access logs)											

