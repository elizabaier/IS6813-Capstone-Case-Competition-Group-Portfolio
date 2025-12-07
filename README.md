# IS6813-Capstone-Case-Competition-Group-Portfolio
University of Utah MSBA Capstone Case Competition Fall 2025 - Swire Coca-Cola Cart Abandonment Project

## Business Problem and Project Objective
Swire Coca-Cola currently faces a significant problem with cart abandonment on their online ordering platform, MyCoke360. Our analysis showed that Swire Cocal-Cola is facing an abandonment rate of 14.8% on the current MyCoke360 platform causing the business to miss out on significant revenue. Our purpose will be to measure, describe, and understand the behaviors that drive cart abandonment to assist Swire Coca-Cola in focusing their efforts to prevent cart abandonment on their MyCoke360 platform.

## Business Problem Solution
Our group created a combined table from different data sets capturing Google Analytics data, customer demographics, confirmed orders, product materials and contracted purchase deadlines. Using this combined dataset, we identified 50,910 purchase windows. Using a comparison of means to examine how frequently different behaviors occur within a purchase window, we found that events such as viewing items and searching for items occurred more frequently in abandoned carts than in non-abandoned carts. Association rule mining provided deeper insight, showing that customers who abandoned carts often became stuck in what we called “friction loops” of updating carts, adding items to carts, and viewing carts. This suggests that customers may be having difficulty finding the right item SKU, correct product size, or the appropriate product type/flavor.

## Business Solution Value


## Group Member Contributions
| Section | Contributor(s) |
|-------|----------|
Introduction | All
Data Preparation | Eliza / Kyle
Independent Variable Analysis | Ashley
Business Demographics | Ashley / Eliza
Correlation Exploration | Lindsey
Feature Engineering | Eliza / Ashley / Kyle
Items & Events and Abandoned Carts | Kyle
Time-Series Analysis | Eliza
Random Forest | Eliza
Hierarchical and GMM Clustering | Ashley
DBSCAN Clustering | Kyle
Association Rule Mining | Ashley
Basic LM | Ashley / Lindsey
Updated LM | Eliza / Ashley
Summary of Findings | Eliza / Ashley
Editing & Compilation | All

## Project Difficulties
We faced several difficulties throughout the project. First and foremost, the data we were given was messy and required many transformations to obtain our final dataset and our target variable. Second, there was no data given from before the treatment period when the MyCoke360 ordering platform was implemented so it was impossible for us to determine the impact of the new ordering platform on cart abandonment. Finally, we lost some data to missing information: 75 rows to missing anchor dates and about 23,000 rows to missing other critical information that we needed to calculate order windows and cart abandonment. Fortunately, we were still left with over 3.6 million rows of data which was plenty to analyze customer behavior surrounding cart abandonment. Overall, this project gave us valuable experience with handling real-world, non-ideal data conditions. 

## Conclusion
