# **World CO₂ Emissions Dashboard**

### Overview
This interactive dashboard visualizes global CO₂ emissions, providing insights into carbon emissions across continents and their relationship with economic factors like GDP per capita. The dashboard allows users to explore CO₂ emissions trends, compare emissions from various sources, and observe how different continents contribute to global CO₂ output over time.

The dashboard is built using Python libraries such as **Pandas**, **Panel**, and **HoloViews**. It leverages data from [Our World in Data](https://github.com/owid/co2-data) and provides a powerful tool for stakeholders interested in environmental data, climate change, and CO₂ trends.

### Features
1. **CO₂ Emission Over Time**: 
   - Explore CO₂ emissions by continent across years.
   - Visualize CO₂ emissions or per capita emissions using a slider and radio button controls.
   
2. **CO₂ vs GDP Scatter Plot**: 
   - Visualize the relationship between CO₂ emissions and GDP per capita for various countries.
   - Understand how economic activity relates to carbon emissions.

3. **CO₂ Sources by Continent**: 
   - Analyze CO₂ emissions by source (coal, oil, gas) across different continents.
   - Interactive bar chart to compare emissions sources by region.

4. **Interactive Data Table**: 
   - Review and filter CO₂ emissions data over time by continent with pagination.

### Key Technologies
- **Pandas**: For data manipulation and analysis.
- **Panel**: To create an interactive dashboard and widgets.
- **HoloViews**: To build dynamic visualizations with minimal code.
- **Bokeh**: For plotting interactive charts and graphs.

### Dashboard Components
1. **CO₂ Emissions Line Chart**:
   - **Widgets**: Year slider, CO₂ metric selector (total emissions vs per capita).
   - **Chart**: Line plot of CO₂ emissions by continent over time.

2. **CO₂ vs GDP Scatter Plot**:
   - **Widgets**: Year slider.
   - **Chart**: Scatter plot comparing GDP per capita to CO₂ emissions for each country.

3. **CO₂ Source Bar Chart**:
   - **Widgets**: Source selector (coal, oil, gas).
   - **Chart**: Bar chart showing CO₂ emissions by source for each continent.

4. **Data Table**:
   - **Widget**: Paginated table of CO₂ emissions data for easy exploration.

### Visual Preview
![CO₂ Dashboard](climate_day.png)
