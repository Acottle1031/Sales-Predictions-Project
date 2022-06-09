# Big Mart Sales
## Predicting Sales for Big Mart 

**Author**: Austin Cottle

### Business problem: 

Our goal here is to create a prediction model for the sales of food items sold at various Big Mart locations


### Data:
Source: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

This data set includes information regarding the sales of products across Big Mart locations over the course of the business life. Including amount of sales, outlet types and tiers, the years the outlet was established and the types of items being sold, among others that are not too useful for us for what we want to do here.



## Methods
- Here we choose to use a Decision Tree model to make predictions. A Decision Tree model is essentially a tool used to make predictions by building series of nodes based on similar features, those nodes are then divided into smaller subsets depending on how deep the model is tuned, and a prediction is made based on the trimmed data.


## Analysis

#### Sales By Item
![sampleimage](https://github.com/Acottle1031/Sales-Predictions-Project/blob/main/items%20sold.png)

This image shows us the sales by item, letting us know that our items that sell the most will be our Fruits & Vegetables, with Snack Foods coming in a very close 2nd.


#### Sales Over Time
![sampleimage](https://github.com/Acottle1031/Sales-Predictions-Project/blob/main/Sales%20over%20time.png)

This image shows us the total sales over time for Big Mart. According to this, they're currently on the up curve, and could potentially maximize by furthering their marketing for other products they sell, such as Household or Frozen Food items since those are performing well but not quite to the level of Snack Foods or Fruits & Vegetables.

## Modeling
#### Linear Regression Predictions Using Scatter Plot
![sampleimage](https://github.com/Acottle1031/Sales-Predictions-Project/blob/main/Scatter%20plot.png?raw=true)]

This visual shows us our predictions for our Linear Regression model against our original testing data. I'm including this as further evidence that the Regression Tree should be used here, as we see the model actually predicted negative values for sales.

#### Regression Tree Predictions Using Scatter Plot
![sampleimage](https://github.com/Acottle1031/Sales-Predictions-Project/blob/main/Regression%20tree%20scatter.png)

This visual shows us our predictions for our Regression Tree model against our original testing data, we can see here comparatively all of the values are a lot more congruent showing us that our model is predicting values very close to our testing values, which is very good!






## Limitations 
This model does make mistakes, our average error for predictions is by about $1,057. This doesnt appear to be bad but I know very little about predicting sales for industries.

## Contact info
I'm extremely new to the coding world so any advice, tips, or recommended reading is greatly appreciated!
I can be reached at a.cottle1031@gmail.com







