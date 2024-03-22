# London-Bike-Ride-Analysis

This project focuses on analyzing London bike rides data using data visualization techniques. The dataset was obtained from Kaggle. The project involved data preprocessing to ensure data integrity followed by creating an interactive London Bike Dashboard using Tableau.

## Dataset Overview

The dataset contains information about bike rides in London, including ride duration, period, start and end dates, weather conditions, temperature, wind speed, and ride counts.

## Project Workflow

1. **Data Preprocessing**:
   - Checked for missing values and data inconsistencies.
   - Ensured data quality by handling null values and other types of errors.

2. **Data Visualization with Tableau**:
   - Created an interactive London Bike Dashboard with customizable filters.
   - The dashboard includes the following main filters:

   - **Moving Average Duration**: Allows to set the duration for the moving average of rides.
   - **Moving Average Period**: Enables to set the period (day, week, or month) for the moving average.
   - **Moving Average Period (Slider)**: Allows to set the start and end dates for the moving average, dynamically updating the line graph.
   
   - Additionally, the dashboard features:
   
   - **Period Selection**: Enables you to drag and select a particular period, which updates other visualizations and trends accordingly.
   - **Total Number of Rides**: Displays the total number of rides, updating according to the applied filters and selected period.
   - **Temperature vs Wind Speed Heatmap**: Shows the sum count of rides based on temperature and wind speed within the selected duration.

3. **Visualizations**:
   - The dashboard includes four main visualizations:
   
   - **Line Graph**: Displays the trend of bike rides over time, adjusted based on the selected moving average duration and period.
   - **Temperature vs Wind Speed Heatmap**: Shows the sum count of rides based on temperature and wind speed.
   - **Weather Condition Heatmap**: Depicts the total rides on different weather conditions (e.g., clear, cloudy, rain, snowfall).
   - **Hourly Rides Heatmap**: Illustrates the total rides during different hours of the day.
   
_Note: The last two visualizations appear on the tooltip when hovering over the heatmap or the line graph._

## How to Use

To explore the London Bike Dashboard and interact with the visualizations:

1. Access the Tableau dashboard via the provided link.
2. Utilize the customizable filters to adjust the moving average duration, period, and date range.
3. Select a specific period by dragging and selecting on the timeline to update other visualizations.
4. Explore the line graph, heatmaps, and tooltips to gain insights into bike rides trends and patterns.

## Resources

- [Link to the Tableau Dashboard](https://public.tableau.com/views/LondonBikeRideDashboard_17104051531480/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)
