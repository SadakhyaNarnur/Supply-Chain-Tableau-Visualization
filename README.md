# Supply-Chain-Tableau-Visualization

Steps to develop
● Data Collection : The dataset is downloaded from Kaggle and stored as csv in drive as
DataCoSupplyChainDataset.
Link:
https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-dataanalysis?
select=DataCoSupplyChainDataset.csv
● Data cleaning : The dataset is read into a Colab Notebook and checked for all the
columns.
Next the dataset is checked for NULL values and it was observed that Order Zip Code
and Product Description had the maximum NULL values and are not really of interest for
our visualization hence dropped the two columns.
Inorder to maintain the anonymity and secure the privacy of customers the columns
regarding any personal data like Customer Email, Customer Fname, Customer Lname
and Customer Password are removed.
● The dataset is too huge and for convenience it is split to Order and customer datasets to
separate the Customers related data from Orders data with still Order Id as common key
in both.
● Importing Data: The two csv files Customer and Order are imported and exported to
Tableau for further analysis.
![image](https://github.com/SadakhyaNarnur/Supply-Chain-Tableau-Visualization/assets/111921205/3d8d8b30-1de7-48bd-83f6-797806134455)

● Sales for Country: The Geospatial chart is visualized as a point map for the orders data
showing the orders over the states in the US based on Latitude and Longitude columns.
The sizes of the points shows the order's intensity in each region of the country.
![image](https://github.com/SadakhyaNarnur/Supply-Chain-Tableau-Visualization/assets/111921205/e8e63a71-94e3-4cd0-b237-d0132ae18bf3)

● Sub Categories by sale: Based on Sales and Categories columns the graph is visualized.
The graph gives a good understanding of the sub categories sales in a descending order
showing the products of focus in years 2015 to 2017.
![image](https://github.com/SadakhyaNarnur/Supply-Chain-Tableau-Visualization/assets/111921205/c31af353-1b26-4955-ab66-5a2bf769465a)

● Sales by product: Based on Products and Sum of Sales bar graph is plotted.
This graph shows the top products ordered by customers which gives a picture of what
are the products that could be focused on.
![image](https://github.com/SadakhyaNarnur/Supply-Chain-Tableau-Visualization/assets/111921205/0efea303-68a9-4794-bc01-fd6225199fea)

● Top Profitable Categories: Top 5 profitable categories are shown based on Category and
Benefit per Order columns.
![image](https://github.com/SadakhyaNarnur/Supply-Chain-Tableau-Visualization/assets/111921205/21370396-05d1-4a19-b161-a3ccb9663e71)

It summarizes the top 5 categories that have been profitable for the company sales.
● Profit/loss summary for products: A tabular summary of Profit/Loss of products is shown
as a tabular format with benefit shown as bar graph.
It gives a good idea of the profits and loss obtained per order of the products.
![image](https://github.com/SadakhyaNarnur/Supply-Chain-Tableau-Visualization/assets/111921205/f53f83f9-60fd-4016-8e7a-afc33d938d15)

● Delivery status by order: A bar chart is visualized based on Delivery status and Order id
columns.
It shows that most of the orders are under late delivery which could be a concern to the
company.
![image](https://github.com/SadakhyaNarnur/Supply-Chain-Tableau-Visualization/assets/111921205/6f509862-20fb-45be-8fcd-d91cd8758d26)

● High demand products based on delivery status: A bar chart to visualize the top 10 highly
demanded products for different delivery status like Advance shipping, late delivery,
shipping canceled and shipped on time. It is built on Product name, Order date, category
and delivery status.
The filter for the graph available gives a good picture of the high demand products for
different delivery status.
![image](https://github.com/SadakhyaNarnur/Supply-Chain-Tableau-Visualization/assets/111921205/04d36f32-aaae-4e7c-9666-aff774e444e4)

● Once all the individual worksheets are prepared on Tableau a dashboard is created with
all these sheets. The graphs are organized into 3 containers for Sales, Profit and Impact to
meaningfully convey the story of the insights obtained.
The Dashboard named “Supply Chain Dashboard” can be seen below:

![image](https://github.com/SadakhyaNarnur/Supply-Chain-Tableau-Visualization/assets/111921205/bde202f1-118e-4bde-8b84-711c438a5163)

