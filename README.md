# Classification-of-Retailers

Background: Case study is sales data for Feb’17 of one area.

Details :

Retailer Name : There are total 9938 unique retailers in this area
Brands : Total 12 different brands can be sold to retailer
Total Sales : This is sum total of sales of all brands
Number of Brands : Total number of unique brands purchased by retailers
Values are in Rupees for Brands Sales and Total Sales
Tip: Retailers can be classified as Category A, B & C. Category A retailers are one who place regular orders and Category C are one who place irregular orders.

Question: How will you classify retailers using sales data of Feb’17. : Please name analytics techniques which can used for classification?
Answer:
As training dataset is not provided, we can not use Supervised learning (Classification algorithms). So only Unsupervised learning (Clustering algorithms) can be used for segmentation.
K-Means Clustering algorithm will be suitable for classification/segmentation of Retailers as we already know that classification has to be done into 3 Categories(A, B & C).

Question: What all variables/data will you use for classification of retailers?
Answer:
Columns/variables 'Brand1', 'Brand2', 'Brand3', 'Brand4', 'Brand5', 'Brand6', 'Brand7', 'Brand8', 'Brand9', 'Brand10', 'Brand11' & 'Brand12' will you use for classification of retailers.
'Total Sales' & 'Number of Brands' are derived columns/variables, means we can find these columns from ['Brand1',.......,'Brand12']. Therefore these columns will not be use for classification.

Conclusion:
Based on Boxplot showing Total Sales of respective Category of Retailer, we conclude that

(1) Category A has highest sales, therefore they will place regular orders.
(2) Category C has lowest sales, therefore they will place irregular orders.

|Category of Retailer|  Frequency of Order  |Number of  Retailers|Average sales per Retailer (Rs.)|
|---|---|---|---|
|A|place regular orders|1|76,18,235.00|
|B|place medium orders|894|79,911.01|
|C|place irregular orders|9043|8,305.47|
