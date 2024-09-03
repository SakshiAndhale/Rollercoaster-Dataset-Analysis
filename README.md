# 🎢 Roller Coaster Data Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Speed vs. Height Correlation](#speed-vs-height-correlation)
  - [Evolution of Roller Coaster Design Over Time](#evolution-of-roller-coaster-design-over-time)
  - [Multi-Variable Interaction](#multi-variable-interaction)
  - [Speed Distribution](#speed-distribution)
  - [Geographical Distribution of Roller Coasters](#geographical-distribution-of-roller-coasters)
  - [Peak Years for Roller Coaster Introductions](#peak-years-for-roller-coaster-introductions)
- [Conclusion and Business Insights](#conclusion-and-business-insights)

## Project Overview
This project focuses on an exploratory data analysis (EDA) of a roller coaster dataset to uncover trends, patterns, and insights. The analysis aims to provide valuable information regarding the evolution of roller coaster designs, their geographical distribution, and key features such as speed and height. 

## Dataset Overview
The dataset includes various attributes related to roller coasters, including:
- **Name**: The name of the roller coaster.
- **Park**: The amusement park where the roller coaster is located.
- **Country**: The country of the amusement park.
- **Year Introduced**: The year the roller coaster was introduced.
- **Type**: The type of roller coaster (e.g., steel, wooden).
- **Speed**: The speed of the roller coaster (in mph).
- **Height**: The height of the roller coaster (in feet).
- **Length**: The length of the roller coaster (in feet).
- **Inversions**: The number of inversions (loops) the roller coaster has.
- **Duration**: The duration of the ride (in seconds).

## Data Cleaning and Preparation
Before analysis, the dataset underwent several data cleaning steps to ensure accuracy and consistency:
1. **Missing Data**: Missing values were identified and handled appropriately, either by imputing them with relevant values or by excluding certain records from the analysis.
2. **Duplicates**: The dataset was checked for duplicate entries, and any found were removed to ensure data integrity.
3. **Data Type Adjustments**: Columns were converted to appropriate data types, such as converting numerical data to integers or floats as needed.
4. **Feature Engineering**: New features were created where necessary to support deeper analysis, such as categorizing roller coasters by their introduction year into different decades.

## Exploratory Data Analysis (EDA)
The EDA explored various aspects of the dataset, with a focus on answering specific questions and providing insights into roller coaster trends:

### Speed vs. Height Correlation
- **Questions Answered**: What is the relationship between the speed and height of roller coasters?
- **Graph Added**: A scatter plot displaying the correlation between speed and height.
- **Observations**: A strong positive correlation was observed, indicating that taller roller coasters tend to be faster.
- **Conclusion**: The correlation suggests that designers leverage height to increase speed, adding to the thrill of the ride.

### Evolution of Roller Coaster Design Over Time
- **Questions Answered**: How have roller coasters evolved in terms of speed and height over the years?
- **Graph Added**: A line chart showing the trend of speed and height over different decades.
- **Observations**: Roller coasters introduced in recent years are generally taller and faster, particularly those from the 2010s onwards.
- **Conclusion**: The evolution reflects advancements in technology and the growing demand for more exhilarating rides.

### Multi-Variable Interaction
- **Questions Answered**: How do variables like speed, height, and year introduced interact with each other?
- **Graph Added**: A pair plot showing the interaction between multiple variables.
- **Observations**: The pair plot analysis confirms a significant correlation between speed and height, with both variables showing an increasing trend over time.
- **Conclusion**: This analysis highlights the complex considerations in roller coaster design, where multiple factors are interrelated.

### Speed Distribution
- **Questions Answered**: What is the distribution of roller coaster speeds?
- **Graph Added**: A histogram displaying the distribution of roller coaster speeds.
- **Observations**: The majority of roller coasters have speeds ranging from 50 to 100 mph, with a peak around 70 mph.
- **Conclusion**: The distribution indicates a common range for speed, aligning with industry standards for thrill and safety.

### Geographical Distribution of Roller Coasters
- **Questions Answered**: Which locations have the fastest roller coasters?
- **Graph Added**: A bar chart showing the speed of roller coasters.
- **Observations**: Notable amusement parks like Busch Gardens Williamsburg, Cedar Point and Six Flags Magic Mountain have the highest concentration of roller coasters.
- **Conclusion**: This insight provides an understanding of regional trends and market saturation in the amusement park industry.

### Peak Years for Roller Coaster Introductions
- **Questions Answered**: What were the peak years for introducing new roller coasters?
- **Graph Added**: A bar chart highlighting the number of roller coasters introduced each year.
- **Observations**: The late 1900s, saw a surge in new roller coaster introductions.
- **Conclusion**: The surge reflects a period of rapid innovation and expansion in the amusement park industry.

## Conclusion and Business Insights
**Final Conclusion:**
- The analysis reveals significant trends in roller coaster design, with a clear evolution towards taller and faster rides over the years. The geographical distribution shows where the highest concentrations of roller coasters are, while the speed distribution highlights industry standards.

**Business Insights:**
- **Design Trends**: The strong correlation between height and speed suggests that future roller coasters will likely continue this trend, emphasizing height as a key factor in ride design.
- **Market Saturation**: Understanding which regions and parks have the most roller coasters can help identify opportunities for expansion or differentiation.
- **Innovation Cycles**: Peak years for roller coaster introductions indicate periods of high innovation, which can be aligned with economic factors and consumer demand.

*This analysis provides a comprehensive understanding of roller coaster trends, offering valuable insights for industry stakeholders looking to innovate and grow in the amusement park sector.* 🚀
