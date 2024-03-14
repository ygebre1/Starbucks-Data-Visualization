# Starbucks Beverage Contents Data Visualization

## Overview
This project visualizes the nutritional contents of various Starbucks beverages using Tableau. The dataset consists of information on calories, sugar content, caffeine levels, and protein content for a range of Starbucks drinks.

## Rationale
In an era where health consciousness is on the rise, consumers are increasingly interested in understanding the nutritional composition of the products they consume. Starbucks, being a prominent player in the beverage industry, attracts a wide range of customers with diverse dietary preferences and requirements. This project aims to provide a comprehensive view of the nutritional aspects of Starbucks beverages, aiding consumers in making informed choices aligned with their health goals.

## Visualizations
### Viz1: Calorie Distribution
- **Methodology:** The visualization starts by grouping similar categories and calculating the average calorie count for each beverage type. These averages are then represented by bars, sorted in descending order to highlight beverages with higher calorie counts.
- **Insights:** This visualization enables viewers to compare the calorie content across different beverage categories, assisting in making healthier choices. For instance, classic espresso drinks tend to have lower calorie counts compared to specialty drinks.
- **Challenges:** Dealing with numerous sub-categories can be challenging, requiring additional steps for data cleaning and organization.

### Viz2: Relationship between Caffeine and Calories
- **Methodology:** This visualization utilizes a scatter plot with caffeine content (mg) on the X-axis and calorie count on the Y-axis. Each data point represents a specific beverage, allowing for easy identification through color-coded marks.
- **Insights:** The scatter plot reveals the relationship (or lack thereof) between caffeine content and calorie count in Starbucks beverages. It may uncover trends or outliers, such as beverages with high calorie counts but low caffeine content.
- **Challenges:** Adjusting for different drink sizes while maintaining clarity can be challenging, requiring data literacy to interpret complex scatter plots effectively.

### Viz3: Sugar and Fat Content Comparison
- **Methodology:** This visualization employs a bar chart where each bar represents a beverage category, with the average sugar content depicted on the Y-axis and different shades of brown indicating fat content. Bars are sorted by increasing average sugar content.
- **Insights:** By highlighting sugar and fat content in each beverage category, this visualization helps consumers identify drinks high in these components. It may also reveal expected trends, such as lower sugar and fat content in simple coffee beverages.
- **Challenges:** The abundance of beverage types can lead to cluttered charts, necessitating careful selection of data for clarity.

### Viz4: Protein Content Overview
- **Methodology:** This visualization utilizes a treemap to display the average protein content of different beverages. Beverages are sorted in descending order of protein content.
- **Insights:** The treemap offers a clear overview of protein content across various Starbucks beverages, identifying drinks with higher protein content. This information can be valuable for individuals seeking protein-rich beverage options.
- **Challenges:** While Tableau provides versatility in data representation, dealing with sub-categories such as beverage preparation may pose challenges in implementing certain visualizations.
