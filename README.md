# Electric Vehicle Data Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)


### Project Overview
***
This electric vehicle (EV) analysis project aims to provide comprehensive insights into the market performance and strategic initiatives of the GM Group's EV lineup over the past year. By analyzing various aspects of EV sales and market data, the goal is to uncover trends, offer data-driven recommendations, and gain deeper insights into operational efficiencies and market positioning.

### Data Sources
The primary datasets utilized for this analysis are sourced from GM Group's internal sales databases, public EV sales reports, and market research data. These datasets provide detailed information about EV sales, market share, customer preferences, and operational metrics.

Vehicle Sales Data: Detailed records of EV sales, including models, sales volumes, and geographical distribution.

Market Research Data: Insights into consumer preferences, competitive analysis, and market trends in the EV industry.

Upcoming Model Data: Details regarding the growth and adoption of electric vehicles (EVs) across different countries and their characteristics.

### Tools:
***
*Excel: Data Cleaning and Initial Analysis
*Python: Data Preparation and Statistical Analysis
*SQL Server: Data Querying and Integration
*Power BI: Visualization, Reporting, and Dashboard Creation


### Data Cleaning and Preparation
***

During the data preparation phase, the following tasks were undertaken:

- Loading and initial inspection of EV sales data.'

- Cleaning and formatting to handle missing values and ensure data integrity.

- Transformation of raw data into structured formats suitable for analysis.

### EDA focused on extracting insights to address key questions in EV analytics:
***

EDA focused on extracting insights to address key questions in EV market analysis:

-What are the trends in GM Group's EV sales over the past year?

-Which GM EV models are most popular among consumers?

-How does charging infrastructure impact EV adoption and sales?

### Data Analysis
***

Some interesting features/Code worked with: 

Example SQL Query:

SELECT model, SUM(units_sold) AS total_sales FROM ev_sales_data WHERE manufacturer = 'GM Group' GROUP BY model ORDER BY total_sales DESC;

***

### Results and Findings
***

Key findings from the analysis include:

- Increasing adoption of GM Group's EV models, with notable growth in specific regions.

- Popular models include the Chevrolet Bolt EUV and GMC Hummer EV.

- Positive correlation between charging infrastructure expansion and EV sales.

### Recommendations
***

Based on the analysis, the following recommendations are proposed:

1. Expand charging infrastructure to support increasing EV sales and customer convenience.

2. Introduce new EV models or variants to capitalize on emerging market trends.

3. Enhance marketing efforts to promote GM Group's EV lineup and increase consumer awareness.

### Limitations
***

Certain limitations were encountered during the analysis:

1. Variability in EV sales data availability across different regions.
2. Regulatory challenges and incentives affecting EV adoption rates.
3. Data privacy considerations impacting the scope of analysis.



