Project goal:  given the increasingly competitive environment that UNIQLO operates in, this report seeks to deliver actionable, multi-dimensional marketing strategies grounded in sales data analysis and visualization. These strategies aim to drive UNIQLO’s sustained growth in revenue and profitability, while reinforcing its leadership in the fast fashion industry amidst intensifying competition.

Flow Chart: 
This part is mainly about the flowchart of this project.  According to the figure 1, it is a flowchart which can clearly display the implementation process of the project.  In the first stage, our group defined the problem as formulating marketing strategies based on sales data analysis to drive UNIQLO’s sustained growth in revenue and profitability.  Then is the data collection stage, our group searched for available datasets by accessing various databases, including Kaggle, CSDN, and Statista.  The collected datasets were reviewed by group discussions to assess the usability.  If a dataset failed to meet the evaluation criteria, the process would return to the data collection stage until a dataset was unanimously approved by our group.  After thorough the group discussion, our group ultimately selected a UNIQLO sales dataset sourced from CSDN.  Next is the data cleaning stage.  To ensure data quality and the reliability of subsequent analysis, the dataset need to be double-checked to make sure everything was properly cleaned.  The core part of this report is data exploration.  Based on initial observations, our group decided to analyze the dataset across four key dimensions to uncover the underlying business insights.  The four dimensions respectively are product dimension, customer dimension, regional dimension and time dimension.  Subsequently, Python was used to visualize the data and conduct in-depth analysis to extract meaningful business implications.  Finally, based on the visualized data and aligned with UNIQLO's current business context, our group developed actionable marketing strategies to support the company’s continued growth. 
![image](https://github.com/user-attachments/assets/83f9d3c9-1724-4ea1-845f-df4643b0464e)

Dataset overview
▪	Data sources
The dataset used in this report was obtained from CSDN, a well-known Chinese developer platform that provides access to a variety of open-source and industry-related datasets. The dataset contains detailed sales records from UNIQLO, including product categories, price, order quantities, revenues, profits, and consumer demographics.

▪	Data cleaning
Before analysis, our group cleaned the data.  As can be seen from the chart, there are so many empty values, they have no meaning, so our group decide to drop all of them.  This ensured that the data was consistent in format, making the analysis results more accurate and the content more reliable.
![image](https://github.com/user-attachments/assets/be93a246-f232-4e7f-92b7-d5c1e715b2a7)
![image](https://github.com/user-attachments/assets/a2f40277-471d-4240-8a03-e688fe39cc94)
![image](https://github.com/user-attachments/assets/1659602f-6b47-495c-bb61-8b3b1a214381)

▪	Descriptive statistics
The dataframe structure of this dataset is 18951 rows × 15 columns .  And, here are the detailed descriptive statistics of UNIQLO's sales dataset.  
![image](https://github.com/user-attachments/assets/9e8b5024-4b9f-4c03-a8a2-a6ede5b65a8a)
![image](https://github.com/user-attachments/assets/69146a26-dc77-4e19-9e8c-f033aa0bb942)
![image](https://github.com/user-attachments/assets/4349ea0a-7ff2-4463-a0b0-657901352872)
![image](https://github.com/user-attachments/assets/5db12767-c1f5-4f92-9e6e-1f8c4a3d4cbb)

Data analysis

In this part, our group analyzed the dataset across four key dimensions to uncover the underlying business insights.  The four dimensions respectively are product dimension, customer dimension, regional dimension and time dimension.

▪	Product dimension
First of all, the below pareto chart is used to analyze the proportion of different products in UNIQLO's total revenue.  The horizontal axis represents the different types of products.  The bar chart represents the total sales of different products, and the line chart represents the cumulative percentage of product sales to total revenue.  It can be seen from the chart that the top three product types in terms of total sales revenue are T-shirt, new product, and accessories. The three products contribute more than 70% of UNIQLO's sales revenue.  According to the 80/20 pattern that focusing on top-performing products could be an effective strategy for revenue growth. 
![image](https://github.com/user-attachments/assets/52017e73-3fc0-4fd9-b6a7-6f31103f32c3)
Next is a boston matrix of product portfolio analysis.  The boston matrix is used to analyze the performance of different categories of UNIQLO products in two dimensions of price and profit.  The bubble chart uses size to reflect product cost, with larger bubbles representing more expensive products.  It is obvious that the "star products" are skirt and accessories. Meanwhile, sock’s profit margin is the highest, but its price is extremely low. Therefore, UNIQLO should continue investing in its star products by ramping up marketing efforts and accelerating new product launches to boost market share and sales revenue. Regarding socks, the company could consider offering more premium options to increase profits without compromising the profit margin.
![image](https://github.com/user-attachments/assets/c5c5376a-f6d6-4cef-bf01-43a3c5a98b71)

▪	Regional Dimension
In the regional performance analysis, the total sales line chart shows that Shenzhen, Wuhan, and Hangzhou have the highest sales, over ¥500,000.  While Nanjing and Beijing fall far below the average line. Similarly, in the total profit line chart, Shenzhen still ranks highest, indicating the robust market presence and operational efficiency in that region.  In contrast, Nanjing and Beijing fall far below the average in both sales and profit. Especially in Beijing, which is a big city with both population density and strong purchasing power but has the lowest performance in both total sales and profit. This is possibly related to product mix, store location, marketing reach, or customer engagement strategies. Shanghai also has high performance above the average in profit. Suggesting a potential for optimization despite being a major economic centre.
![image](https://github.com/user-attachments/assets/5ffed3a2-11ef-4af8-9218-d1a5765b6148)
![image](https://github.com/user-attachments/assets/5132c471-d43e-4c6a-8b39-f86db58afef8)

On the other hand, in online and offline sales analysis across cities, our group find that most cities still rely heavily on offline sales, especially in Shenzhen and Hangzhou. While Wuhan has the highest presence in online shopping, this indicates they may have a better digital adoption or marketing strategy. UNIQLO could analyze Wuhan's strategy and assess if similar models can be duplicated in other regions to reduce over-reliance on physical stores.
![image](https://github.com/user-attachments/assets/092452ce-cc6c-4726-bd64-622a12283faa)
For improving the total sales, UNIQLO can refer to the heatmap because it provides further details and clearly shows that T-shirts and accessories are the top-selling categories in almost all cities, especially in Shenzhen and Hangzhou. This suggests that consumer preferences in these regions are stable and consistent. 

Also, it is important to customize strategies based on different demands in different locations. UNIQLO can refer to the heatmap to see which products sell well in each city. For example, in cities where stores sell a lot such as Shenzhen and Hangzhou, UNIQLO can confidently increase the inventory of top-selling categories in these cities to avoid best-sellers sold out in these cities and enhance revenue. 
In cities where online shopping is growing, such as Wuhan, there is an opportunity to experiment with new product lines or limited online exclusives, using online shopping platforms as an experiment ground. This strategy could help to encourage digital engagement, make more customer willing to shop through online platforms, click “like” and commend their preferred items. This would also help UNIQLO to gather feedback from customer and adjust their product based on that feedback.
![image](https://github.com/user-attachments/assets/4a069ea9-4d75-4c2c-aaa1-3ec1656cce44)

Conclusions

Consistent with the data analysis section, our group developed marketing strategies from four dimensions to help UNIQLO achieve sustained growth in both revenue and profitability, while maintaining its leadership position in the fast fashion industry.

▪	Product dimension
Among the nine product categories analyzed, T-shirt, accessories, and new product are the core products of UNIQLO, both in terms of profitability and consumer preference.  Therefore, UNIQLO should continue investing in these core products by ramping up marketing efforts and accelerating new product launches to boost market share and sales revenue.  In additon, as the product with the highest profit margin at UNIQLO, socks are limited by their inherently low price. However, UNIQLO can still consider launching more premium, higher-priced sock products to further increase overall profits.

▪	Customer dimension
UNIQLO's customers are mainly young people aged 20 to 39. UNIQLO should focus on this group's dual pursuit of leisure and fashion, and attract consumption through continuous innovative designs and social media marketing. Furthermore, women's consumption accounted for more than 70% of the total sales. UNIQLO needs to further expand the women's clothing market, including developing new women's clothing lines and marketing activities targeting the female group.

▪	Regional dimension
Shenzhen, Wuhan and Hangzhou account for more than 50% of the total sales. For these cities, UNIQLO should increase its branches and design marketing plans based on local characteristics. In addition, UNIQLO should actively expand its sales channels and promote online sales in more cities.

▪	Time dimension
Weekend sales are significantly higher than weekday sales. UNIQLO should increase promotional activities and boost product supply on weekends to meet consumer demand. At the same time, UNIQLO could take inspiration from KFC’s “Crazy Thursday” strategy and introduce limited-time discounts on Wednesdays to stimulate midweek consumption.
 


