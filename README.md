# Company-Sales-Dashboard
This dashboard provides a comprehensive performance overview for a sales team across multiple Indian cities. It is designed to track individual employee contributions, total sales volume, and target achievement metrics through both tabular data and visual analytics.
Objectives
The primary goal of this system is to transform raw sales logs into actionable business intelligence through:
• Regional Benchmarking: Comparing performance across cities like Mumbai, Delhi, and Pune.
• Individual Accountability: Tracking specific employee codes (e.g., MumTCL-002) to identify top performers and those needing intervention.
• Target Synchronization: Providing a real-time look at how much of the monthly or quarterly goal has been "hit" versus what is still "away."
VLOOKUP formulas to create a relational structure between raw sales data and employee master records. This ensured data integrity across all four dashboard views.
• Dynamic Data Retrieval: Used to fetch Employee Names and Target Quotas based on unique Emp_code (e.g., MumTCL-002).
• Automated Calculations: Leveraged VLOOKUP to pull "Target" values from a secondary sheet to calculate the Target Hit % and Target Away % shown in Dashboards 3 and 4.
Key Features
• One-Click Updates: By using Pivot Tables, the dashboard can be updated with new monthly data simply by refreshing the data source.
• Error Reduction: VLOOKUP eliminates the risk of manual entry errors when mapping names to employee codes.
