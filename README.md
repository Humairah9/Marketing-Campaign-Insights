# Marketing-Campaign-Insights
I performed an EDA on a digital marketing dataset using Microsoft Excel and Python to uncover key performance drivers. The analysis revealed patterns in customer behavior, ROI trends, and engagement across channels, demographics, and regions.

# Table of Content
- [Introduction](https://github.com/Humairah9/Marketing-Campaign-Insights/blob/main/README.md#introduction)
- [Dataset Overview](https://github.com/Humairah9/Marketing-Campaign-Insights/blob/main/README.md#dataset-overview)
- [Tool Used](https://github.com/Humairah9/Marketing-Campaign-Insights/blob/main/README.md#tools-used)
- [Cleaning and Transformation](https://github.com/Humairah9/Marketing-Campaign-Insights/blob/main/README.md#data-cleaning--transformation)
- 

![image](https://github.com/user-attachments/assets/25d50196-4b5b-44b6-ab55-de8982aebb17)

# Introduction 
In today's competitive digital marketing landscape, data-driven decision-making is essential for maximizing campaign effectiveness. This report presents an in-depth exploratory data analysis (EDA) of a marketing campaign dataset, offering valuable insights to optimize spending and enhance performance. 
The analysis focuses on identifying the most effective marketing channels, tracking conversion rates and ROI trends, evaluating customer engagement levels, and uncovering patterns across different target audiences and locations. These insights provide a data-backed foundation for refining strategies, improving cost efficiency, and making informed decisions to drive better campaign outcomes.

# Dataset Overview
The marketing campaign dataset, provided by the HNG Internship Program, includes the following key attributes:
Campaign Information: Campaign ID, Company, Campaign Type, Target Audience, Duration, and Marketing Channel.
Performance Metrics: Conversion Rate, Acquisition Cost, Return on Investment (ROI), Clicks, Impressions, and Engagement Score.
Demographics: Location and Customer Segment.
Time-Based Information: Campaign Date.
Dataset Summary:
Total Observations: 200,005
Total Va
Total Variables: 15
Data Types: Numeric, Categorical, and Date formats
Tools
Python; The primary language for data manipulation.
Regular Expression(re); To clean text data and remove unwanted patterns
Matplotlib; For data visualization, helping to analyze and display patterns.

# Tools Used 
The tools used for this project is Python and Microsoft Excel

# Data Cleaning & Transformation
Data cleaning and transformation were done using Microsoft Excel and Python. In Excel, missing values were identified, text inconsistencies in 'Channel' and 'Location' were corrected, and key metrics like CTR, CPC, Conversion Rate, and ROI were calculated. In Python, the cleaned data was loaded, data types were verified, missing values checked, and outliers visualized using boxplots and the IQR method.

# Insights
- Boxplots analyzed the distribution of key metrics, including Conversion Rate, ROI, Acquisition Cost, Clicks, and Impressions. Outliers in ROI and CPC indicated significant variations, suggesting some campaigns performed exceptionally well or poorly.
- Marketing channel analysis showed that Email and Google Ads were the most cost-effective.
- A bar chart compared average ROI across channels, while a scatter plot analyzed CTR vs. CPC.
- A line chart tracked CTR trends over time.
- The correlation heatmap revealed a positive link between CTR and ROI, while Acquisition Cost had a weaker impact on success.

 # Visualizations
 ![image](https://github.com/user-attachments/assets/5566189e-fb24-4493-9334-c9a1f0b39243)
 ![image](https://github.com/user-attachments/assets/4d29ca5d-e734-4594-8304-cbdfa16bbea5)

# Conclusion
This analysis highlights top marketing channels, audience segments, and locations for optimization. Facebook and Email had the highest ROI, while Men (25-34) showed the best engagement.

# Recommendation
Prioritizing Miami and Los Angeles and optimizing CPC for Google Ads and YouTube can improve cost efficiency. Regular trend monitoring will enhance budget allocation.













