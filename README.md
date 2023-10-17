# Fast Food Nutrition Analysis 

## Overview
This dataset, originally sourced from Kaggle, provides nutrition information for five different chain restaurants, including Burger King, Wendy's, KFC, Taco Bell, and Pizza Hut.  The data is located on Sheet 1 of the Excel document. Please note that the dataset was last updated on October 16, 2023, and may not reflect the most current menu items. The data is categorized into three meal types: Breakfast, Lunch/Dinner, and Drinks/Desserts. For each meal type, there are several metrics, including average calories, total fat, sodium, sugar, and grams of protein per menu item. The dataset is in Excel format, and for the analysis, Microsoft Excel was used.
This analysis is intended for those who seek a quick bite to eat while getting a fix to whatever craving or food they are wanting to have. This data analysis will help users decide if they want something sweet (sugar) or salty (sodium);  a fatty item (total fat) or something filled with protein (protein). The averages of these attributes have been computed for each restaurant.

## Data Structure
![image](https://github.com/ashley-ley/fast-food-nutrition/assets/132225987/f35b7d7c-2962-45a6-bb38-4f273c85799a)

The data is structured as follows:
+ Each fast-food chain's data is presented in its respective section, with separate tables for each meal type.
+ For each metric (calories, total fat, sodium, sugar, and protein), you will find the calculated average and the percentage of daily intake values for both women and men.
+ If there is no data for a particular meal type or metric for a specific fast-food chain, it is indicated in the table.
+ In cases where data is missing, it has been counted as "0" for calculations.
  
## Example Usage
Here's how you can interpret and use this dataset:
+ If you want to know the average number of calories for Breakfast items at Burger King, refer to the "Burger King's Food Nutrition Data" section under the "Breakfast" table.
+ To find the percentage of daily intake for women and men for Lunch/Dinner items at KFC, look for the relevant values in the "KFC's Food Nutrition Data" section under the "Lunch/Dinner" table.
+ If you are interested in comparing the sugar content of Drinks/Desserts at Taco Bell vs Burger King, navigate to the "Taco Bell's Food Nutrition Data" and “Burger King’s Food Nutrition Data” sections and look under the "Drinks/Desserts" for each respective table.

## Key Insights

![image](https://github.com/ashley-ley/fast-food-nutrition/assets/132225987/17acc307-36a4-4883-aa71-4ba27827e0cf)
+ Burger King stands out with the highest average sodium per menu item for both Breakfast and Lunch/Dinner, representing 81% and 72% of the recommended daily sodium intake, respectively. In contrast, McDonald's has the lowest average sodium intake for Lunch/Dinner menu items, amounting to 51% of the recommended daily sodium intake per menu item.
+ Burger King’s menu items have an average of 28 grams of protein per lunch/dinner menu item, amounting to 61% and 50% of the amount of protein needed daily for women and men respectively. 
+ McDonald’s breakfast has an average of 437 calories, making that the best breakfast choice for those who are looking for low calorie meals. However, these meal items still account for 22% and 17% of the daily recommended daily for women and men respectively.
+ Although Taco Bell has some breakfast menu items, they were not included in this dataset. KFC and Pizza Hut do not have breakfast so no data was available there. 
+ An important thing to note about Pizza Hut is the data is broken down by slice. The average number of calories found is broken down by slice, not by pizza. The average pizza slice has 253 calories. 

## Dataset Integrity
Please note that while efforts have been made to provide accurate and up-to-date information, the dataset might not reflect the most current menu items or nutritional data. It's essential to verify the accuracy of the data and refer to official sources for the latest nutritional information from the fast-food chains.

## Future Developments
As the project evolves, there is a plan to develop more insightful visualizations to provide deeper insights into the data. I would like this visualization/dashboard to allow users to pick a restaurant of their choosing, then further select which menu item they desire. Then, data would appear about each menu item. This will further assist users in making informed decisions regarding their fast-food choices.

## Acknowledgments
The data for this analysis was originally collected from Kaggle and was compiled for informational purposes.
