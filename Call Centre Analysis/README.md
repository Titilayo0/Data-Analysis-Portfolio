# Power BI Call Center Analysis

# Executive Summary

This project focuses on analyzing call center performance using Power BI. It provides insights into key metrics such as total calls, number of agents, agents response, average satisfaction rating, agent performance, where customers need response, call volume by month and customer satisfaction. The goal is to improve operational efficiency and enhance customer experience through data-driven decision-making.

## Project Summary

The Call Center Analysis Dashboard is designed to:

1. Monitor call volumes, answered vs. unanswered calls, and resolution rates.

2. Analyze agent performance based on call handling metrics.

3. Measure customer satisfaction using ratings and resolution status.

4. Identify trends by date, time, and weekday to optimize workforce management.

## Project Scope

1. Call Performance Analysis: Track total calls answered vs. unanswered, analyze average talk duration per agent.

2. Agent Productivity & Case Resolution: Evaluate case resolution rates per agent, Compare resolved vs. unresolved cases, Identify top-performing and underperforming agents.

3. Customer Satisfaction & Trend Analysis: Track satisfaction ratings over time, Analyze call patterns by weekday and month. Identify peak call times and areas for improvement.

## Dataset Used

The dataset includes:

| Feature                       | Description                                      |
|--------------------------------|--------------------------------------------------|
| Call ID                        | Unique identifier for each call                  |
| Agent                          | The customer service representative handling the call |
| Date & Time                    | Timestamp of when the call occurred              |
| Topic                          | Subject of the customer inquiry                  |
| Answered (Y/N)                 | Whether the call was answered                    |
| Resolved                       | Indicates if the issue was resolved              |
| Speed of Answer (Seconds)      | Time taken to answer the call                    |
| AvgTalkDuration                | Average talk time per call                       |
| Satisfaction Rating            | Customer feedback score                          |
| Talk Duration                  | Total duration of the call                       |
| Calls Answered & Unanswered    | Total count per agent                            |
| Case Resolved & Unresolved     | Number of cases resolved vs. unresolved         |
| Weekday                        | Day of the week for trend analysis              |


## Methodology

### Data Cleaning & Processing:

Remove duplicates and missing values.

Standardize date and time formats.

### Data Modeling:

Create relationships between tables for seamless analysis.

Generate calculated columns and measures using DAX.

### Visualization & Dashboard Development:

Design interactive charts, tables, and KPIs in Power BI.

Implement filters for agents, topics, and time periods.

## Key Performance Indicators (KPIs)

Total Calls Answered – Number of successfully handled calls.

Total Calls Unanswered – Calls that were not picked up.

Average satisfaction rating - satisfaction rating of agents

Average Talk Duration – Time spent on each call.

Average satisfaction Rating – Percentage of cases successfully resolved.

Satisfaction Score – Customer rating of the service received.

Peak Call Hours – Identifies high call volume times.

## Conclusions

Key Findings:

1. High unanswered call rates may indicate understaffing during peak hours.

2. Certain agents consistently resolve cases faster and more effectively.

Peak call times occur between specific days of the month and weekdays, requiring better resource allocation.

Customer satisfaction scores fluctuate based on call resolution efficiency.

## Recommendations:

Increase staffing during peak hours to reduce unanswered calls.

Provide additional training to agents with low resolution rates.

Automate responses for common inquiries to improve efficiency.

Monitor and adjust agent schedules based on real-time data trends.
