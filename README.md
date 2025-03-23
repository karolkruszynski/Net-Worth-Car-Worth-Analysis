# LINK TO KAGGLE NOTEBOOK
https://www.kaggle.com/code/karolkrusznyski/net-worth-car-worth-analysis

# About Dataset
The sales prediction dataset comprises historical data on sales transactions, including factors such as date, product type, store location, and sales revenue. Our analysis aims to uncover trends, seasonality, and other patterns within the data to develop predictive models for future sales. By leveraging statistical methods and machine learning algorithms, we seek to forecast sales accurately, helping businesses optimize inventory management, marketing strategies, and overall performance. This dataset provides valuable insights for businesses aiming to improve their sales forecasting capabilities and maximize profitability.

# What I've done
## Read Dataset
## Simple Analysis through Dataframe
* df.describe()
* df.info()
* df.columns
* df.isnull().sum()
* df.rename(columns=columns_to_rename, inplace=True)
* df.drop(['customer_name', 'customer_email'], axis=1, inplace=True)
* df['gender'] = df['gender'].map({1:'Male', 0:'Female'})
* df['age'] = df['age'].astype(int)

## More Advanced Analysis
### How does age affect annual earnings?
### What is the relative credit card debt to car value based on annual income?
### Is there a correlation between net wealth and car value?
### What percentage of annual income is credit card debt for different age groups?
### Is there a correlation between age and car value?
### AND CONCLUSION FOR ALL OF THE TOPICS ABOVE
