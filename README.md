# Walmart Competitor Analysis

## Project Overview
This project analyzes competitive retail market conditions to determine the best locations for launching a new retail store that will compete with Walmart and Target. The objective is to identify the top 10 markets using a data-driven approach by evaluating sales, competition, demographics, and other key factors.

## Objectives
1. **Identify the best locations** based on competitor sales and market saturation.
2. **Analyze market demand** by evaluating total and per square foot sales.
3. **Examine the impact of holidays** on sales performance.
4. **Assess competition levels** by determining underserved markets.
5. **Make data-driven recommendations** for the best store locations.

## Dataset & Variables
### Data Sources
- Historical sales data from Walmart (or Target equivalent) [2010-2012].
- Demographic datasets at DMA (Designated Market Area) level.
- MSA (Metropolitan Statistical Area) data for consumer expenditure insights.
- Competitor store location data.

### Key Variables Used
- **Store**: Store number
- **Dept**: Department number
- **Date**: Weekly sales period
- **Weekly_Sales**: Sales revenue per department per store
- **IsHoliday**: Indicator for holiday periods
- **Temperature, Fuel Price, CPI, Unemployment**: Economic and external factors
- **MarkDowns**: Promotional sales reductions
- **Square Footage**: Store size for sales efficiency comparison
- **Competitor Count**: Number of competitor stores per region

## Methodology
### 1. **Market Selection Criteria**
- **Sales Performance**: Identified markets with the best and worst total sales and average weekly sales per square foot.
- **Competition Analysis**: Counted competitor stores per location to identify underserved markets.
- **Holiday Sales Impact**: Weighted holiday performance 5x higher than non-holiday weeks to evaluate market volatility.
- **Demographics & Consumer Behavior**: Used DMA and MSA datasets to assess household income and expenditure patterns.

### 2. **Data Cleaning & Processing**
- Removed incomplete or inconsistent data.
- Standardized store and location identifiers.
- Calculated mean and median sales metrics.
- Applied data visualizations to interpret findings.

### 3. **Visualization & Insights**
- **Competitor Distribution**: Plotted number of competitor stores per DMA.
- **Sales Trends**: Created time-series graphs of weekly sales per store and region.
- **Holiday Sales Impact**: Analyzed average sales spikes around Thanksgiving, Christmas, Super Bowl, and Labor Day.
- **Top & Bottom Markets**: Identified best and worst performing stores based on sales and foot traffic.

## Key Findings
- **Best Locations for New Stores**:
  - **Minneapolis-St. Paul**: No competitors, high-income households, strong consumer spending.
  - **New York**: No competition, highest consumer unit count (7.5M potential customers).
  - **Seattle**: No competition, highest annual spending on food & personal care.
  - **Boston**: High-income city with no competition, strong consumer expenditure.
  - **Miami**: No competitors, mid-income city with high spending on household goods.
  - **Los Angeles**: High sales per store despite seven competitors, significant market demand.
  - **Chicago**: Underserved market with 1.2M consumers per store.
  - **Orlando-Daytona Beach-Melbourne**: Only one competitor, strong sales potential.
  - **Charlotte**: Two competitors but high sales per square foot potential.
  - **Kansas City**: Underserved market, large store footprint reducing competitor efficiency.

- **Best Performing Markets**:
  - **Highest Total Sales**: Los Angeles (largest number of stores and highest revenue).
  - **Highest Sales per Square Foot**: Austin (small store sizes with high efficiency).
  - **Best Holiday Performance**: Houston, Tampa, and Orlando were top markets across holidays.
  
- **Worst Performing Markets**:
  - **Lowest Total Sales**: Kansas City.
  - **Lowest Sales per Square Foot**: Denver.
  - **Underperforming Stores**: Stores in Salt Lake City, Austin, Denver, and Atlanta consistently had the lowest average weekly sales.

## Recommendations
- Prioritize expansion into **Minneapolis, New York, Seattle, and Boston** due to the lack of competitors and strong income levels.
- Open smaller-format "light" stores in **Los Angeles, Chicago, and Charlotte** to optimize sales per square foot.
- Monitor **Kansas City and Denver** for potential improvements or alternative strategies due to weak market performance.
- Capitalize on high holiday sales in **Orlando, Houston, and Tampa** for promotional strategies.

## Tools & Technologies
- **Programming Language**: R (ggplot2, dplyr)
- **Data Visualization**: ggplot2, tables, bar graphs, and time series analysis
- **Data Sources**: Walmart sales dataset (Kaggle), DMA & MSA demographic datasets

## Contributors
- **Author**: Mira Kapoor Wadehra (https://github.com/mirakw).
- **Professor**: Houldsworth (MGSC-410-01)

## License
This project is for educational and analytical purposes. The dataset and code are shared under open-source terms where applicable.

