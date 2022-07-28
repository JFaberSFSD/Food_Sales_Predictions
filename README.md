# Food Sales Predictions
## A Deep Dive Into Outlet Sales 

**Author**: Justin Faber

### Business problem:

What metrics influence total outlets sales? Is there a way that we can better predict sales based on historical information? Let's find out! 


### Data:
We're going to start this journey with historical sales information. 8,523 rows of it to be exact! We have information such as what type of item was sold, its visibility in the store, the size of the store, and the total sales. Hopefully this will be enough data for us to build our model! 


## Methods
- To prepare our data for this project we did the following:
  - Removed any duplicate rows from within our dataset
  - Explored any missing values from within our data
    -  Most missing data we were able to locate the correct value based on other information from within the data itself (ex: item weight by item identifer)
    -  The remaining misisng values (whcih were all in the 'Outlet_Size' column) - we simply marked as "unknown" so that we could keep the rest of our data in there
  -  Categorical columns with inconsistent values were fixed
    -  For example, the 'Item_Fat_Content" column had 'Low Fat" marked in three different ways: 'Low Fat', 'LF', and "low fat". These were consolidated into just "Low Fat" for consistency
  -  We looked for any potential outliers from within our dataset, but found nothing so far outside of the norm that warranted removal, so we left all remaining data in the dataset for further exploration!

## Results
Our first goal was to better understand our data, and some of the bigger takeaways we could make initially. The first thing I wanted to better understand was which categories produced the largest sales volume? Certainly this would be a focal point if your goal is to predict overall sales. I wanted to take a look at the top three item categories for sales between our different oulet types


#### Top Categorical Sales - by Outlet Type
![VIZ 1](Final_Project_Visualization_1.png)

> Sentence about visualization.

#### Visual 2 Title

## Model

Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact **email**
