# Customer segmentation for E-Commerce
## This project is an attempt to classify the customers into different categories using unsupervised learning(k-means clustering) and  supervised learning classifiers using [E-Commerence data](https://archive.ics.uci.edu/ml/datasets/online+retail) and decide the best classifier based on the values of accuracy. 

In this project many machine learning libraries present in Python are used to perform different operations. KNN, Random Forest, Gradient Boost are the supervised learning algorithms used and an accuracy of 68.29, 75.50, 75.77 was achieved respectively during testing.

### [Paper](https://www.researchgate.net/publication/355166048_Customer_Segmentation_in_E-_Commerce)
### Project background
#### With the growth of the market, it has become mandatory for the old businesses to apply marketing strategies to stay in the market due to the increase in competition. The number of consumers is increasing significantly every day and it has become challenging for the businesses to cater to the requirements of every and each customer. Hence Customer segmentation is used which is the process of dividing customers into groups with respect to the common characteristics by which the companies can target each group efficiently. It allows companies to see what actually the purchasers are buying which can prompt the businesses to better serve their customers leading to customer satisfaction, it also allows the businesses to seek out who their target customers are and improvise their marketing tactics to get more revenues from them.

### Data
#### Features
##### This dataframe contains 8 variables that correspond to:

1. InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
2. StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
3. Quantity: The quantities of each product (item) per transaction. Numeric.
4. InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
5. UnitPrice: Unit price. Numeric, Product price per unit in sterling.
6. CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
7. Country: Country name. Nominal, the name of the country where each customer resides.