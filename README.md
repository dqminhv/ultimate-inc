Ultimate Inc
============

This repository contains a comprehensive data analysis project exploring driver behavior and login patterns, as well as a detailed experimental design to evaluate a policy's impact on driver activity. The analysis is divided into two main parts, emphasizing data wrangling, visualization, and practical experimentation:

## **Part 1: Exploratory Data Analysis (EDA)**

1. **Data Preparation**: The dataset is imported, cleaned, and processed. Additional columns such as 'date' and 'time' are derived from the original data, and logins are categorized into 15-minute intervals.
2. **Login Pattern Analysis**: The analysis includes counting logins by time intervals, identifying patterns in the data, and creating time series visualizations. The notebook explores daily and weekly trends in login behavior.
3. **Visualization and Insights**: Various plots, including boxplots and time series visualizations, help highlight key trends, such as peak login periods during late nights and midday. Weekday and weekend patterns are contrasted, showing distinct behaviors.

**Key Insights**:
* Two peak login periods are observed: late night (00:00 to 03:00) and midday (10:30 to 13:00).
* Login behavior differs between weekdays and weekends, with Friday nights and weekend mornings showing notable activity.

## **Part 2: Experimental Design for Policy Evaluation**

1. **Success Metric**: The project identifies the primary success metric as the increase in the number of drivers crossing a toll bridge.
2. **Experiment Outline**: A two-phase experiment is proposed to measure the impact of a reimbursement policy for drivers, collecting data before and after implementation. A hypothesis test is then conducted to assess the policy's effectiveness.
3. **Evaluation and Recommendations**: A statistically significant increase in toll crossings would indicate the success of the policy, providing data-driven recommendations for further action.

This repository provides an example of effective data exploration, visualization, and hypothesis testing to support policy decision-making. It serves as a resource for analysts seeking to understand driver behavior through data and to design experiments that evaluate business strategies.

