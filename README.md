# Air Quality and Its Impact on Health and Life Quality Indicators

## Project Overview
This data analysis project investigates the relationship between air quality (measured by PM2.5 levels) and various life quality indicators, including asthma hospitalizations, happiness index scores, and life expectancy. By analyzing data from multiple sources and examining trends across countries and years, I aim to uncover potential correlations and insights into how environmental factors like air pollution may influence public health and overall well-being.

This project is part of my portfolio as a data analyst and highlights my skills in data cleaning, analysis, visualization, and storytelling. It combines environmental and social datasets to provide a comprehensive view of the potential impacts of air quality on health and life quality.

## Objectives
1. **Assess the Relationship Between Air Quality and Health/Life Quality Indicators**:
   - Explore correlations between PM2.5 levels and asthma hospitalizations, happiness scores, and life expectancy across different countries.
2. **Identify Patterns and Trends**:
   - Investigate if countries with lower PM2.5 levels consistently show better health and life quality outcomes.
3. **Provide Actionable Insights**:
   - Generate insights that highlight the importance of air quality in shaping public health and life quality, potentially guiding policy discussions or further research.

## Data Sources
- **Air Quality Data**: Historical PM2.5 data from [WAQI](https://waqi.info/) measuring daily concentrations of particulate matter across multiple countries.
- **Asthma Hospitalizations**: Data on annual asthma-related hospital admissions in the USA from 2015 to 2021 from the [CDC Tracking Network](https://ephtracking.cdc.gov/).
- **Asthma Prevalence**: Global asthma prevalence data from [Our World in Data](https://ourworldindata.org).
- **Happiness Index**: Annual happiness scores and rankings from the [World Happiness Report](https://worldhappiness.report) covering 2015 to 2019.
- **Life Expectancy**: Life expectancy data from the [World Bank](https://databank.worldbank.org/source/world-development-indicators).

Each dataset was cleaned and prepared to ensure compatibility for analysis.

## Analysis and Findings

Presentation can be found at: https://docs.google.com/presentation/d/1K7BxNxXMc4oSLgfDFzIrVxpB9zMQ5V5ky_1AicE9YLw/edit?usp=sharing

### 1. Air Quality and Asthma Hospitalizations (USA)
- **Objective**: To explore the impact of air quality on asthma-related hospitalizations within the United States.
- **Methodology**: Merged PM2.5 data with asthma hospitalization rates, focusing on different states over multiple years.
- **Findings**: A moderate positive correlation was observed, suggesting that states with higher PM2.5 levels experienced more asthma-related hospitalizations. However, air quality alone may not fully explain hospitalization rates, as other factors like healthcare access and socioeconomic conditions likely play a role.

### 2. Air Quality and Happiness Index (Global)
- **Objective**: To examine whether countries with better air quality tend to rank higher on the Happiness Index.
- **Methodology**: Merged PM2.5 levels with happiness scores and rankings. Analyzed trends across different countries and years.
- **Findings**: Countries with lower PM2.5 levels generally scored higher on the Happiness Index. A moderate negative correlation was found between PM2.5 levels and happiness scores, suggesting that better air quality may contribute to higher happiness levels. Nonetheless, happiness is multifaceted, and air quality is just one of many factors influencing overall well-being.

### 3. Air Quality and Life Expectancy (Global)
- **Objective**: To investigate the potential relationship between air quality and life expectancy across various countries.
- **Methodology**: Merged PM2.5 data with life expectancy data, categorized air quality into levels (Good, Moderate, Unhealthy, etc.), and compared average life expectancies within each air quality category.
- **Findings**: A negative correlation was observed, where countries with lower PM2.5 levels (better air quality) had higher life expectancies. However, life expectancy is influenced by multiple factors, including healthcare, lifestyle, and socioeconomic conditions, and air quality is just one contributing factor.

### Key Insights
- Countries with lower PM2.5 levels generally have better outcomes across various life quality indicators, including lower asthma hospitalizations, higher happiness scores, and longer life expectancy.
- While air quality appears to play a role in influencing health and quality of life, it is one of many factors at play, and causation cannot be assumed from correlation alone.
- This analysis highlights the potential importance of environmental quality in shaping public health and well-being, suggesting that efforts to reduce pollution may contribute positively to various aspects of life quality.

## Project Structure

The project is organized as follows:
- **Data Cleaning Notebooks**: Jupyter notebooks dedicated to cleaning and preparing each dataset for analysis. Each notebook outlines the steps taken to clean, filter, and merge the data as needed.
- **Data Analysis Notebooks**: Analysis notebooks focusing on specific relationships between PM2.5 and each life quality indicator. Each notebook includes detailed markdown sections with objectives, methodology, results, and interpretations.
- **Images Folder**: Contains saved visualizations from the analysis, such as scatter plots, line graphs, and bar charts used in the final analysis and report.
- **README File**: Provides an overview of the project, data sources, objectives, and key findings.

## Technologies and Skills Demonstrated
- **Python**: Used for data manipulation, analysis, and visualization, primarily using pandas, matplotlib, and scipy.
- **Data Cleaning and Preparation**: Comprehensive cleaning of multiple datasets from diverse sources to ensure compatibility and consistency in analysis.
- **Data Analysis and Visualization**: Detailed exploratory data analysis (EDA) and visualization to uncover patterns, trends, and insights.
- **Statistical Analysis**: Correlation and regression analysis to identify relationships between air quality and various health and life quality indicators.

## Conclusions
The project demonstrates a significant association between air quality (measured by PM2.5 levels) and various indicators of life quality, including asthma rates, happiness scores, and life expectancy. While air quality is likely a contributing factor to public health and well-being, it should be considered alongside other variables such as healthcare access, economic conditions, and lifestyle factors. This project underscores the importance of environmental quality and offers insights that may inform policy decisions or further research on the intersection of environmental and social determinants of health.

## Next Steps and Future Research
- **Further Analysis**: Include additional variables, such as GDP, healthcare quality, and education levels, to build a more comprehensive model of factors affecting life quality indicators.
- **Time-Series Analysis**: Conduct a more detailed time-series analysis to observe trends and potential lag effects of air quality changes on health outcomes.
- **Regional Studies**: Investigate regional variations to understand how specific policies or environmental factors influence health and life quality outcomes locally.

## Acknowledgments
This project was developed using open-source data from the World Happiness Report, Our World in Data, WAQI, the CDC, and the World Bank. Special thanks to these organizations for making their data publicly available and accessible for analysis.

---

By including this project in my portfolio, I hope to showcase my ability to handle complex data analysis tasks, interpret correlations, and generate actionable insights that may inform real-world decision-making related to public health and environmental policy.

