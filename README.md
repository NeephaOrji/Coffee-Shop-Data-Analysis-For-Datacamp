# Coffee-Shop-Data-Analysis-For-Datacamp

This project aims to provide insights for a brand that recycles coffee cups and is looking to improve sales by distributing directly to stores rather than relying solely on their websites. The analysis focuses on answering three key business questions to help them understand the market and make informed decisions. The data used for the analysis was collected from various regions, and includes information on the place, reviews, and their relationship.

## Data Sources

The data used for this analysis was collected from various marketplaces. The data includes information on the type of place, reviews, and their relationship. 

## Business Questions

The analysis aims to answer the following three business questions:

1. What is the most common place type in the market?
2. What is the distribution of reviews in the market place?
3. What is the relationship between reviews and place type in the coffee shop industry?

## Methodology

The analysis will be conducted using the following libraries: numpy, matplotlib.pyplot, pandas, seaborn. 

The data was be cleaned and processed using pandas to  check for duplicates, replace missing values with appropraite values, and drop outliers. The data was  then be visualized using matplotlib.pyplot and seaborn to better understand the distribution of reviews and the relationship between reviews and place type. 

To answer the first question, we used a countplot and the order of place types with decreasing popularity are; Coffee Shops, Cafes, Others and Espresso Bars.

To answer the second question, we removed outliers and used histograms to visualize the distribution of reviews in the market place. 

To answer the third question, we used boxplots to visualize the relationship between reviews and place type. 

## Conclusion

For a start, Cups should be distribited to **Coffee Shops and Cafes** with reviews between **450 and 1000**. Further analysis is required for the relationship between reviews and region.
