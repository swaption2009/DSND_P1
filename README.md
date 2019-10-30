##Write a Data Science Blog Post

Please find the blog post and analysis of this GitHub repo [here](https://medium.com/@JontanJon/udacity-data-scientist-project-seattle-airbnb-data-7f34d18598d4).

##Motivation for the project
Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA.

For this Udacity Data Scientist Nanodegree first project, we are using Seattle AirBNB data to analyze the following three business questions:
1. What is the relationship between monthly price and number of reviews?
2. What is the relationship between monthly price and neighborhood areas?
3. Can We Predict the Monthly Price based on Certain Parameters?

##Summary of the results of the analysis
1. For the first question, we don't find any correlation between monthly price and number of reviews.
2. On the second question, we use data visualization to show some relationship between monthly price and neighborhood.
3. For the last question, we use `sklearn` library and `Linear Regression` to train and predict monthly price based on 5 features selection.

##How to use the files in this repository 
- `seattle` folder consists of Kaggle Seattle AirBNB data in csv format.
- `workbook.ipynb` is the Jupyter Notebook to preprocess and analyze the data.
- `workbook.html` is the HTML file for quick viewing on the browser.
- `README.md` provides the intro and summary of the analysis.

##Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
