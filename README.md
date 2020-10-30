# Analyzing-Global-SuperstoreSales-Data:

To practice my data visualization skills using Python, I’m exploring a very popular data for visualization. I’m using Global Superstore data which is available online. To visualize the data, I’m using popular python libraries like Matplotlib, Seaborn, and Wordcloud. There are a total of *24 variables and around 50,000 records*. To explore the data, I started by checking the null values. Postal Code variable had around 80% null values. So, I removed the variable. A couple of variables like Product ID, Row ID, Order ID are not relevant when it comes to visualization. So, I deleted these three columns. Later, I checked the data types for each column to avoid issues while plotting. I converted data types of two variables to DateTime. Performed data summarization to get an overview of the numerical variables. Once, I was done with the cleaning process, I started visualizing the data to answer business questions.


Some of the business questions are:
1. Count of Orders per Year
2. Sales and Profit per Year
3. Shipping Cost for each type of shipping modes
4. Top customers based on Orders
5. Most profitable segments
6. Analyzing discount rates
7. Top Countries by Sales and Profit
8. Top Markets by Sales
9. Top Product Names (Wordcloud)


**The different types of plots used are Distribution plots, Heat map for correlation, Bar plot, Scatter plot, and Line charts.**


**Python Libraries: NumPy, Pandas, Scipy, Matplotlib, Seaborn**


