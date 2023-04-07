# Sales Predictions
## Analyzing how outlet and product features affect outlet sales for particular products
Taylor Brown

There is a question as to whether things like outlet and item characteristics affect how well an item sells at  

Here is the Data Dictionary for this dataset:

![image](https://user-images.githubusercontent.com/125171441/230619836-c6399916-489f-4336-9f15-eb5e0ba9e23c.png)

### To prepare this data, the data was cleaned and the following processes were performed:

#### Exploratory Data Analysis

For exploratory purposes, a boxplot and numerous bar graphs were used to get a better understanding of which categorical columns had the most noticiable differences.

![image](https://user-images.githubusercontent.com/125171441/230620944-09c9c523-33b1-4974-ab90-b5e74ec598f3.png)

This graph shows that most items are fruits and vegetables or snack foods.

#### Explanatory Data Analysis

For more explanation, a histogram and regression plots were created to better understand sales.

![image](https://user-images.githubusercontent.com/125171441/230621321-a55e1c28-6a1f-481a-a67f-5f751139f1d6.png)

This histogram shows that the distribution in sales shows an almost $300 difference between the mean and median pricing.

#### Machine Learning using the following models:
Linear Regression model
Decision Tree model

### Models Evaluated and Results

Linear Regression Model
- RMSE for Training data: 1123.8998444176802
- RMSE for Testing data: 1138.8930792786596
- R2 for Training data: 0.5695255660827053
- R2 for Testing data: 0.5434402534179733

Decision Tree Model
- RMSE for Training data: 0.0
- RMSE for Testing data: 1529.9966964730718
- R2 for Training data: 1.0
- R2 for Testing data: 0.17602753884643552

The final model chosen was the decision tree with a max depth of 5.

- RMSE for Training data: 1068.429642057492
- RMSE for Testing data: 1100.0684740167412
- R2 for Training data: 0.6109691893038818
- R2 for Testing data: 0.5740377148242786

Though the initial reading for the decision tree had polarizing calculations, the tuned model shows reliable data that can predict sales within $1100 using the categorical data available.

#### Limitations and Next Steps

From here, a person can further investigate other possible characteristics that may affect how a customer views products and how they purchase them.

#### For further information
For any additional questions, please contact me at taylorshelannbrown@gmail.com
