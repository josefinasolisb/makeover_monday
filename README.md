# makeover_monday
## Generative AI Search Trends in the United States
This visualization presents the search trends related to generative artificial intelligence (AI) across different regions in the United States. The purpose of this analysis is to explore the popularity of various generative AI topics within different geographic areas. The data used for this visualization consists of search percentages for different generative AI topics, such as "Midjourney," "Stable Diffusion," and "DALL E," aggregated by region.
[Data Source](https://data.world/makeovermonday/generative-ai-search-trends-in-the-united-states)

###Data Description
The dataset contains search percentage data for generative AI topics across various regions in the United States. Each row represents a specific region, and columns represent different generative AI topics. The search percentage indicates the relative popularity of each topic within a specific region.

###Data Adjustments
The names of this dataset were corrected to be more pythonic. Also the percentages were tranformed to numeric values, specifically to integers so that the bar plot could be performed without problems. 

###Visualization
The code for adding the data to the plot was made using a function in order for this code to be scabalable and be used with other datasets that contain more columns. The bar plot visualizes the search trends for generative AI topics in the United States. Each bar represents a specific generative AI topic, and the height of the bar corresponds to the search percentage. The x-axis denotes different regions, while the y-axis represents the search percentage.
