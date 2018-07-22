# Capstone-Project-1

Capstone1: AirBNB Price Point... Still a work in progress...

When visiting a city for the first time or renting out your home it can be a struggle figuring out if you are getting a fair price for the AirBNB rental or whether you priced your home appropriately to make a profit. The purpose of this project is to use machine learning to calculate a fair approximate value for a home to assist renters and hosts using AirBNB.

The data used for this project was pulled from AirBNB’s website by Tom Slee (http://tomslee.net/airbnb-data-collection-get-the-data). The dates of the data are from 26 randomly selected days over the past five years. I downloaded all the separate csv files for each date using glob and joined them together to form one large dataframe. The data used totals 159,181 rows for the city of Chicago.

The approach for solving this problem will be taking the random data samples for Chicago and performing exploratory data analysis along with data wrangling. After the data is cleaned, a linear regression machine learning model will be applied to predict the values of the homes and a feature importance analysis will be run to sort contributing value importance. Later the data will be explored using supervised regression models including decision tree, random forest, k-nearest neighbors, multi-layer perceptron, gradient boosting, lasso regression, ridge regression and elastic net. These results will all be tied together to see the impact each factor may have on overall price. The deliverables for this project will be the code, a report detailing the work completed and a blog post telling the story.
