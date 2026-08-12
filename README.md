# Evaluating Production Bottlenecks Through Downtime Analysis

# Business Challenge
As GreenTech Manufacturing grows, it has encountered persistent challenges in its production schedules, which are often impacted by unplanned downtime. This downtime stems from a combination of factors, including:

- Machine Failures: Equipment malfunctions or unexpected breakdowns that halt production.

- Material Shortages: Delays in raw materials or inadequate inventory levels leading to stoppages in production.

- Inefficient Production Planning: Poorly optimized production schedules that lead to idle time or excessive machine changeovers.

- Manual Scheduling: The current scheduling system is heavily reliant on manual input, which can lead to errors, misalignments, and inefficiencies.

- Limited data visibility: This prevents proactive identification of bottlenecks.


Key Impact Areas:

1. Operational Inefficiency: The production lines experience downtimes leading to wasted labor and unused machine time.

2. Financial Costs: Downtime directly impacts revenue, with an estimated loss of $1.5 million annually due to production delays and inefficiencies.

3. Customer Delays: Failure to meet production deadlines leads to delays in fulfilling orders, impacting customer satisfaction and relationships.

4. Resource Wastage: Inefficient scheduling leads to overstocking of certain materials while others run out, contributing to wastage and additional costs in inventory management.

The inability to optimize production schedules and minimize downtime is therefore a significant issue for GreenTech, impacting its ability to meet growing demand while maintaining its sustainability goals.

Optimizing production schedules to minimize downtime is a critical initiative for GreenTech Manufacturing, especially as the company continues to grow and scale its operations. Efficient production scheduling is not just a matter of improving internal processes but also an opportunity to enhance customer satisfaction, reduce costs, and improve overall operational efficiency.

Industry Relevance:

Consumer Goods Sector: Companies in the consumer goods industry often face challenges with balancing production demand, supply chain constraints, and equipment reliability. Downtime can result in costly delays and a poor customer experience. Therefore, optimizing production schedules to reduce downtime is essential for maintaining competitive advantage.

Technology Adoption: Many mid-sized manufacturers are adopting modern tools like Business Intelligence (BI) and data analytics to analyze production data and optimize scheduling. These technologies enable companies to make data-driven decisions, improving productivity while minimizing operational bottlenecks.

# Top Five Reasons for Initiating this Project:

1. Improved Decision-Making: Data-driven insights from production and scheduling analytics will empower management to make better decisions, avoid costly mistakes, and prioritize improvements.

2. Increased Production Efficiency: Optimizing schedules will reduce idle time on production lines, leading to higher throughput and improved capacity utilization.

3. Cost Reduction: By minimizing downtime and production delays, GreenTech can reduce unnecessary labor costs, avoid overstocking inventory, and decrease wastage, improving the bottom line.

4. Enhanced Customer Satisfaction: On-time deliveries will improve customer relationships, ensuring that products reach clients without delays and fostering long-term loyalty.

5. Scalability: Optimizing the production process will enable GreenTech to scale its operations more efficiently as demand grows, allowing the company to meet customer needs without sacrificing quality or delivery timelines.

# Project Objectives
The main objective of this project is to optimize GreenTech Manufacturing’s production schedules to minimize downtime, reduce operational costs, and increase overall efficiency. By implementing a data-driven approach to production planning, the company aims to identify and address bottlenecks, improve scheduling accuracy, and streamline production processes.

Specific Objectives:

1. Identify Root Causes of Downtime: Analyze downtime records to determine key contributors (machine, material, operator error, etc.)

2. Optimize Production Scheduling: Use production and downtime data to create efficient schedules that minimize overlaps and idle time.

3. Improve Operator Allocation: Ensure no operator runs overlapping shifts and optimize shift-to-product assignments.

4. Enhance Reporting Transparency: Develop Power BI dashboards for real-time monitoring of production performance and downtime metrics.

5. Enable Continuous Improvement: Establish a data feedback loop that supports continuous optimization and strategic planning.

# Comprehensive Dataset

For this project, the following datasets will be required to ensure data integrity, relevance, and accuracy in optimizing production schedules:

A. Products (Dimension Table)

1. Product_ID: Unique product identifier

2. Product_Name:Product name (e.g., Ecowash, BioWipe, Packaging Film)

3. Description: Description of each product

4. Category: Category of each product (e.g EcoCleaning Suppies)

5. Size: Product volume or weight

6. Min_Batch_Time: Expected production time per batch

B. Line Productivity (Fact Table)

1. Date: Production date

2. Product_ID: Product reference

3. Batch_ID: Unique 6-digit batch number (prefixed by Product ID)

4. Operator: Responsible production line operator

5. Start_Time: Date/time column signifying the batch production start date and time

6. End_Time: Date/time column signifying the batch production end date and time

7. Planned_Min_Batch_Hours: Expected production time per batch in hours

C. Line Downtime (Fact Table)

1. Batch_ID: Associated batch with downtime

2. Factor_1 to Factor_13: Downtime minutes

D. Downtime Factors

1. Factor_ID: Unique ID for downtime factors

2. Factor_Name: Name corresponding to each factor id

3. Description: Description of factor ids in text

4. Operator Error: Boolean indicating whether downtime is caused by operator or not

# Technology Stack

To address the business challenge of optimizing production schedules, the following technology stack will be used:

1. Microsoft SQL Server:

- SQL Server will be used as the centralized database to store all production and downtime data
- SQL Server’s robust querying capabilities will allow for detailed analysis and reporting of production and downtime patterns.

2. Power BI:

- Power BI will be used to create dynamic and interactive dashboards that allow real-time tracking of production schedules, downtime reasons, and key performance indicators (KPIs) such as equipment uptime, material availability, and production efficiency.
- Power BI’s advanced visualizations will provide decision-makers with actionable insights into production performance.

# Methodology



 






