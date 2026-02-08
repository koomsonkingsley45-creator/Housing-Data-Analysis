# Housing-Data-Analysis
I built this project to master the end-to-end data analysis process. By cleaning raw data, performing exploratory analysis, and building a visual dashboard, I have demonstrated my ability to turn complex housing datasets into clear, professional insights.

# 1. Project Overview
For my first data project, I worked on a housing dataset to see what actually makes a house more expensive. I used Microsoft Excel to go through the raw data, clean it up, and look for patterns. The main goal was to take a messy list of house details and turn them into clear information that could help someone buying or selling a home understand the market better.

# 2. Problem Definition
The main problem I tried to solve was: **"Which specific house features have the biggest impact on the final sale price?"** Instead of just guessing, I wanted to use the data to see if things like having a basement or air conditioning actually justify a higher price tag.

# 3. Data Understanding
The dataset contains several columns that describe each property. The key ones I focused on are:
•	Price: The total cost of the house (the main thing I am trying to explain).
•	Area: The size of the property in square feet.
•	Bedrooms/Bathrooms: The count of rooms which usually affects family appeal.
•	Furnishing Status: Whether the house is furnished, semi-furnished, or unfurnished.
•	Main road/Basement/AC: "Yes/No" columns that show if the house has these specific features.

# 4. Data Cleaning
Before doing any math, I had to make sure the data was "healthy." Here are the steps I took:
1.	Handling Blanks: I checked for any empty cells. For the price and area, I made sure there were no missing numbers so the averages wouldn't be wrong.
2.	Removing Duplicates: I used the "Remove Duplicates" tool in Excel to ensure no house was counted twice.
3.	Standardizing Text: I noticed some text had weird spacing or different capitalizations, so I fixed those to make the categories consistent.
4.	Formatting: I converted the whole range into an Excel Table (Ctrl + T) because it makes writing formulas much easier.

# 5. Exploratory Data Analysis (EDA)
I used Excel formulas and Pivot Tables to find the "story" in the numbers:
•	Descriptive Statistics: * The Average price of a home in this set is about ₵4,767,740.
o	The cheapest house (Min) was significantly lower, while the most expensive (Max) reached over ₵13,000,000.
•	Correlations: I noticed that as the Area (square footage) increases, the Price usually goes up, which makes sense.
•	Pivot Table Insights: I created a table to see the average price based on Furnishing Status.
o	Result: Furnished homes consistently cost more than unfurnished ones.

# 6. Visualizations
I created a dashboard to make the data easier to see at a glance.
•	Price Distribution (Histogram): This showed me that most houses in the dataset are in the "Low" to "Mid" price range.
•	Area vs. Price (Scatter Plot): This confirmed a positive trend—bigger houses generally cost more. 
•	Furnishing Status (Pie Chart): This helped me see the percentage of the market that is fully furnished versus unfurnished.

The visualizations are displayed below:
# Dashboards
![Housing Dashboard 1](https://github.com/user-attachments/assets/ef04e42b-ee0d-4370-9cd6-6a9a4b77fe34)
![Housing Dashboard 2](https://github.com/user-attachments/assets/b2f11d95-30d2-4a33-bb8b-4f8870dcd5f1)

# Tables

![Table 2](https://github.com/user-attachments/assets/b7e3457f-257a-4785-af96-24a2f5f39629)
![Table 3](https://github.com/user-attachments/assets/ab37f257-9fd4-4bda-a27c-8692895b8ff2)
![Table 4](https://github.com/user-attachments/assets/d8b6d6dd-6f9c-4a17-8ded-eda95556881c)

# 7. Interpretation & Key Insights
After looking at the charts, here is what I discovered:
•	Major Influencers: Air Conditioning (AC) and being on a Main Road seem to be huge factors. Houses with AC are almost always in the higher price brackets.
•	Value Segments: There is a "sweet spot" in the mid-range where you get a decent-sized house (4,000–6,000 sq ft) without the "luxury" price tag of the very large estates.
•	Trends: Most buyers seem to be looking for semi-furnished homes, as they make up a large portion of the data.

# 8. Recommendations
If I were advising a real estate agent or a builder based on this data, I would suggest:
1.	Prioritize AC: Since AC has such a strong link to higher prices, adding cooling units to a "Low" tier house is likely the fastest way to increase its resale value.
2.	Focus on Mid-Sized Lots: Because most houses are in the 5,000 sq ft range, developers should focus on this size to stay within the most active part of the market.
3.	Marketing Basements: Medium-priced homes often have basements; highlighting this feature can help a seller move their property from the "Low" category to "Medium."

# 9. Conclusion 
This project helped me see how data can take the guesswork out of real estate. By cleaning the data and using Pivot Tables, I was able to prove that while size (area) is important, 
