# Quality Coffee Analysis  
![coffee](https://github.com/DBulnes97/Quality-Coffee-Analysis/assets/109225064/0b3c5639-eb74-4f1c-a28b-984db5e7b62e) 

From time to time and to survive the adult life we need the empowering beverage that keeps us awake and give the boost required to make the task less daunting and exhausting, and that beverage it's the coffee. The coffee has a lot of varieties across the world and it's dependent of the transformation process from coffee bean to the cup of coffee. To understand how the varieties change we need to focuse in the coffee quality analysis.

The next repository digs in the coffee quality analysis by developing a data analysis in his steps: 
1. Brief Explanation of Coffee Quality Analysis
2. Coffee Quality Bussiness Problem
3. Scope of Work Document of Coffee Quality
4. Summarize of Coffee Quality Dataset
5. Analysis of Coffee Quality in Python.
6. Key Insights of Coffee Quality
7. Visualizations of Coffee Quality Analysis.  

# Brief Explanation of Coffee Quality Analysis. 
Coffee quality analysis involves various parameters that are assessed to determine the overall quality of coffee. These parameters provide valuable insights into the characteristics and flavor profile of the coffee. Here is a summary of some commonly used coffee quality analysis parameters and their mean values:

* **Acidity:** Acidity refers to the sharp, tangy taste in coffee and is an important factor in determining its overall flavor. The mean acidity value for high-quality coffee typically falls within the range of 7 to 9 on a scale of 1 to 10.

* **Body:** Body describes the physical sensation and weight of the coffee in the mouth. It can range from light and delicate to full and heavy. The mean body value for good-quality coffee generally falls between 6 and 8.

* **Aroma:** Aroma relates to the fragrance and smell of the coffee. It encompasses a wide range of scents, including floral, fruity, nutty, and chocolaty notes. The mean aroma value for excellent coffee usually ranges from 8 to 9.

* **Flavor:** Flavor encompasses the overall taste experience of the coffee, including the combination of acidity, sweetness, bitterness, and other characteristic notes. The mean flavor value for top-quality coffee is typically around 8.

* **Balance:** Balance refers to the harmony and integration of different flavors in the coffee. It is the proper blending of acidity, sweetness, and bitterness, resulting in a well-rounded and pleasant cup. The mean balance value for premium coffee generally falls between 7 and 9.

* **Aftertaste:** Aftertaste is the lingering taste that remains in the mouth after swallowing the coffee. A desirable aftertaste is long-lasting, clean, and enjoyable. The mean aftertaste value for high-quality coffee typically ranges from 7 to 9.

![coffee_tasting_flavor_wheel](https://github.com/DBulnes97/Quality-Coffee-Analysis/assets/109225064/b8c3b1de-332a-4b0e-a279-3e0759c9adbb|widht=20)

It's important to note that these mean values are general guidelines, and coffee quality can vary based on various factors such as origin, processing methods, roast level, and personal preferences. Additionally, coffee quality analysis often involves a sensory evaluation by trained professionals who assess these parameters subjectively, considering their individual expertise and taste preferences. If you want to know more about coffee quality and the production process of coffee you can check out this video: 
[Coffee Basics](https://www.youtube.com/watch?v=vFcS080VYQ0) 
[Everything you've ever wanted to know about coffee | Chandler Graf | TEDxACU](https://www.youtube.com/watch?v=N8meCjVsJWI)

# Coffee Quality Business Problem
The main business problem we are going to analyze here it's related to the trends on the world related to coffee quality parameters. Coffee companies strive to maintain high-quality standards for their products. However, without effective quality control measures, there can be issues such as defects, contamination, or inconsistencies in flavor profiles. These problems can result in rejected batches, increased costs, and customer complaints. The next questions arise from the analysis: 
1. What countries have the highest coffee quality parameters?
2. What are the trends of coffee quality around the world?
3. What is the most used method of coffee production?
4. The altitude plays a important role in the coffee production?
5. Which countries have more coffee production farms? 

# Scope of Work of Coffee Quality Analysis
The scope of work of this analysis it's going to be related to identify the profile trends of coffee quality parameters, identify which methods can be used to obtain high quality coffee production during all the transformation process and also to look for the coffee quality market around the world. This will consist in three mildstones steps during the analysis: 
1. **Cleaning and Formatting:** this step will be focused on deliver the state of the dataset: security, bias and completness of the dataset, in addition to steps of cleaning and formatting steps of the analysis.
2. **Statistical Analysis:** this step will be focused on deliver the trends of coffee quality parameters around the world to answer the business questions related with this dataset. 
3. **Insights and Visualization Analysis:** this last step will be focused on deliver the insights analysis by presenting the most impactul visualizations around the coffee quality analysis. 

# Summarize of Coffee Quality Dataset
The Coffee Quality Dataset has the next information related to the data: 
* **Data Source:** Coffee Quality Institute (https://database.coffeeinstitute.org/)
* **Data Location:** Kaggle from Fathi. B
* **Data last update:** 1 month ago.
* **Data Time Interval:** 2018 to May 2023.
* **Privacy:** Public Dataset from Kaggle.
* **Credibility and Bias:** At first impression the data it's not biased and has credibility by the data source of coffee quality institute updated to may of 2023.

# # Columns of Coffee Quality Dataset 
The columns in the Coffee Quality Dataset are 41 with the respective information: 
1. Unnamed: data type int64.
2. ID: data type int64. 
3. Country of Origin: data type object.
4. Farm Name: data tyoe object
5. Lot Number: data type object
6. Mill: data type object
7. ICO number: data type object
8. Company: data type object
9. Altitude: data type object
10. Region: data type object
11. Producer: data type object
12. Number of Bags: data type int64
13. Bag Weight: data type object
14. In-Country Partner: data type object
15. Harvest Year: data type object
16. Grading Date: data type object
17. Owner: data type object
18. Variety: data type object
19. Status: data type object
20. Processing Method: data type object
21. Aroma: data type float64.
22. Flavor: data type float64.
23. Aftertaste: data type float64.
24. Acidity: data type float64.
25. Body: data type float64.
26. Balance: data type float64.
27. Uniformity: data type float64.
28. Clean Cup: data type float64.
29. Sweetness: data type float64.
30. Overall: data type float64.
31. Defects: data type float64.
32. Total Cup Points: data type float64.
33. Moisture Percentage: data type float64.
34. Category One Defects: data type int64
35. Quakers: data type int64.
36. Color: data type object
37. Category Two Defects: data type int64.
38. Expiration: data type object
39. Certification Body: data type object
40. Certification Address: data type object
41. Certification Contact: data type object
In total there are 207 elements for each column and in total of nulls are: 153 of the total dataset. 

