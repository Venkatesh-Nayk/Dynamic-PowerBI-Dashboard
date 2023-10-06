# Used_Cars Data Analysis 

## About Dataset:
- Dataset includes 6000+ used cars with details such as make, model, manufacturer, price, production year, fuel type, selling states, and kilometers driven.
- Provides insights into the used car market, including popular models, manufacturers, and average prices in different states or regions.
- Year of production and kilometers driven offer additional information on vehicle age and condition.
- Fuel type data can help identify regional consumer preferences.
- This dataset is a comprehensive tool for understanding and analyzing the dynamic used car market from various angles.

<br>

## <img src="https://user-images.githubusercontent.com/122404051/235767211-297f9f4f-d41a-46ec-838f-13ea23817702.gif"  width="48" height="48"> Data Preparation:

![excelsheet](https://user-images.githubusercontent.com/128036066/235987911-b62660a6-1485-4fda-af9f-947f280d3d24.png)

To prepare the data, we performed the following steps using the Power Query Editor:
  1. Dropped nulls, blank rows, and duplicate rows.
  2. Created a "Row ID" column as the unique identifier for each row, starting from 1000 with an increment of 1 for each row.
  3. Changed the data types of the columns accordingly.
  4. Created two new columns from the car_name column: "Brand" and "Car model".
  5. Removed the original "car_name" column.

## Data Analysis:
We analyzed the data to gain insights into the used car market, including the following:
  1. Relationship between the age of a used car and its price.
     
     <img src="https://github.com/Venkatesh-Nayk/Dynamic-PowerBI-Dashboard/assets/129421850/528ef831-be55-42f3-9c40-406062a7cbe0" alt="Image Description" height="250" width="500">

  2. Top 10 brands based on the average price.
     
     <img src="https://github.com/Venkatesh-Nayk/Dynamic-PowerBI-Dashboard/assets/129421850/7483690e-1182-46ee-9848-6e304258ddc6" alt="Image Description" height="250" width="500">

  3. Percentage of used cars in different cities for cars whose price is greater than 10 Lakh.
     
     <img src="https://github.com/Venkatesh-Nayk/Dynamic-PowerBI-Dashboard/assets/129421850/126af0f8-f2c1-4c9c-a2ef-bc9be29705f6" alt="Image Description" height="250" width="500">

  4. Number of cars in low, middle, and high-end categories based on price and fuel type.
     
     <img src="https://github.com/Venkatesh-Nayk/Dynamic-PowerBI-Dashboard/assets/129421850/55f607aa-95cd-49b2-8732-24887553b89d" alt="Image Description" height="250" width="500">

 
  <br>

## Dashboard

![image](https://github.com/Venkatesh-Nayk/Dynamic-PowerBI-Dashboard/assets/129421850/e20277fb-8a04-4883-aeca-63401a4e2288)
<br>

## Evaluation Criteria
We evaluated our dashboard based on the following criteria:
  1. Use of interactive filters and slicers to allow users to customize the data being displayed.
  2. Use of clear and concise data labels to provide additional context for data points.
  3. Proper alignment and spacing of visualizations.
  4. Appropriate font size and color scheme.
  5. Clear and concise titles for visualizations, reports, and dashboards.
  6. Use of appropriate background color to improve the visibility of visualizations.

## Conclusion:
Our analysis of the used car sales dataset revealed several interesting insights that can be valuable for businesses operating in the used car market. Through the use of Power BI, we were able to transform and visualize the data in a way that allowed us to gain a deeper understanding of the market trends.

Firstly, we cleaned the data by removing null, blank and duplicate rows, and created a unique identifier for each row. We also changed the data types of the columns accordingly. Furthermore, we created two new columns - brand and car model - from the car_name column, which gave us a better understanding of the popular car brands and models in the market.

We then analyzed the relationship between the age of a used car and its price, which allowed us to determine that the older a car is, the lower its price tends to be. We also created a visualization that showed the relationship between the age of a used car and its price, which provided a clear understanding of this relationship.

Next, we created a bar chart that showed the top 10 brands based on the average price, with the city and count of cars in that city in the tooltip. This provided insight into the popular car brands in different cities, and how they compare in terms of pricing.

We also created a pie chart that showed the percentage of used cars in different cities for cars whose price is greater than 10 Lakh. This provided valuable insights into the distribution of used cars in different cities and the popularity of the used car market in these cities.

In addition, we created a calculated column to divide the cars into three categories - Low End, Middle End, and High End - based on their price. We then created a bar chart to show the number of cars in these categories, with fuel type as the legend. This provided insights into the popularity of different price categories and how they relate to fuel type.

We then created a multi-row card visualization that showed the average, min, and max price of cars, the average kilometers driven by all the cars, and the total number of cars in the dataset. This provided a comprehensive overview of the used car market.


