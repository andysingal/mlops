Feature engineering is the process of selecting, manipulating and transforming raw data into features that can be used in supervised learning. It’s also necessary to design and train new machine learning features so it can tackle new tasks. A “feature” is any measurable input that can be used in a predictive model. It could be the color of an object or the sound of someone’s voice. Feature engineering is the act of converting raw observations into desired features using statistical or machine learning approaches.

## Feature Engineering Definition
Feature engineering is the process of selecting, manipulating and transforming raw data into features that can be used in supervised learning. It consists of five processes: feature creation, transformations, feature extraction, exploratory data analysis and benchmarking. 
 

## Feature Engineering Processes
Feature engineering consists of various processes:

1. Feature creation: Creating features involves creating new variables which will be most helpful for our model. This can be adding or removing some features. 
2. Transformations: Feature transformation is simply a function that transforms features from one representation to another. The goal here is to plot and visualize data. If something isn’t adding up with the new features, we can reduce the number of features used, speed up training or increase the accuracy of a certain model.
3. Feature extraction: Feature extraction is the process of extracting features from a data set to identify useful information. Without distorting the original relationships or significant information, this compresses the amount of data into manageable quantities for algorithms to process.
4. Exploratory data analysis : Exploratory data analysis (EDA) is a powerful and simple tool that can be used to improve your understanding of your data, by exploring its properties. The technique is often applied when the goal is to create new hypotheses or find patterns in the data. It’s often used on large amounts of qualitative or quantitative data that haven’t been analyzed before.
5. Benchmark : A benchmark model is the most user-friendly, dependable, transparent and interpretable model against which you can measure your own. It’s a good idea to run test data sets to see if your new machine learning model outperforms a recognized benchmark. These benchmarks are often used as measures for comparing the performance between different machine learning models like neural networks and support vector machines, linear and non-linear classifiers or different approaches like bagging and boosting.

## Importance of Feature Engineering
Feature engineering is a very important step in machine learning. Feature engineering refers to the process of designing artificial features into an algorithm. These artificial features are then used by that algorithm in order to improve its performance, or in other words, reap better results. Data scientists spend most of their time with data, and it becomes important to make models accurate.

<img width="585" alt="Screenshot 2024-05-05 at 5 58 10 PM" src="https://github.com/andysingal/mlops/assets/20493493/0a8dcb4c-2d34-42d8-b1fe-e33c9500517a">

Feature Engineering Explained
Image: Shutterstock / Built In
Brand Studio Logo
UPDATED BY
Brennan Whitfield | Apr 29, 2024
Feature engineering is the process of selecting, manipulating and transforming raw data into features that can be used in supervised learning. It’s also necessary to design and train new machine learning features so it can tackle new tasks. A “feature” is any measurable input that can be used in a predictive model. It could be the color of an object or the sound of someone’s voice. Feature engineering is the act of converting raw observations into desired features using statistical or machine learning approaches.

Feature Engineering Definition
Feature engineering is the process of selecting, manipulating and transforming raw data into features that can be used in supervised learning. It consists of five processes: feature creation, transformations, feature extraction, exploratory data analysis and benchmarking. 

In this article we’ll cover:

What is feature engineering?
Importance of feature engineering.
Feature engineering techniques for machine learning.
Best tools for feature engineering.
 

What Is Feature Engineering?
Feature engineering is a machine learning technique that leverages data to create new variables that aren’t in the training set. It can produce new features for both supervised and unsupervised learning, with the goal of simplifying and speeding up data transformations while also enhancing model accuracy. Feature engineering is required when working with machine learning models. Regardless of the data or architecture, a terrible feature will have a direct impact on your model.

To better understand it, let’s look at a simple example. Below are the prices of properties in x city. It shows the area of the house and total price.

Sample data for feature engineering.
Sample data for feature engineering. | Image: Harshil Patel
This data might have some errors or might be incorrect but not all sources on the internet are correct. To begin, we’ll add a new column to display the cost per square foot.

Adding new sample data column.
Adding new sample data column. | Image: Harshil Patel
This new feature will help us understand a lot about our data. So, we have a new column which shows cost per square foot. There are three main ways you can find any error. You can use Domain Knowledge to contact a property advisor or real estate agent and show him the per square foot rate. If your counsel states that pricing per square foot can’t be less than $3,400, you may have a problem. The data can be visualized this way:

Bar graph for home prices.
Bar graph for cost per square footage. | Image: Harshil Patel
When you plot the data, you’ll notice that one price is significantly different from the rest. In the visualization method, you can readily notice the problem. The third way is to use statistics to analyze your data and find any problem.

MORE ON MACHINE LEARNING
Machine Learning Basics Every Beginner Should Know

 

Feature Engineering Processes
Feature engineering consists of various processes:

Feature creation: Creating features involves creating new variables which will be most helpful for our model. This can be adding or removing some features. As we saw above, the cost per sq. ft column was a feature creation.
Transformations: Feature transformation is simply a function that transforms features from one representation to another. The goal here is to plot and visualize data. If something isn’t adding up with the new features, we can reduce the number of features used, speed up training or increase the accuracy of a certain model.
Feature extraction: Feature extraction is the process of extracting features from a data set to identify useful information. Without distorting the original relationships or significant information, this compresses the amount of data into manageable quantities for algorithms to process.
Exploratory data analysis : Exploratory data analysis (EDA) is a powerful and simple tool that can be used to improve your understanding of your data, by exploring its properties. The technique is often applied when the goal is to create new hypotheses or find patterns in the data. It’s often used on large amounts of qualitative or quantitative data that haven’t been analyzed before.
Benchmark : A benchmark model is the most user-friendly, dependable, transparent and interpretable model against which you can measure your own. It’s a good idea to run test data sets to see if your new machine learning model outperforms a recognized benchmark. These benchmarks are often used as measures for comparing the performance between different machine learning models like neural networks and support vector machines, linear and non-linear classifiers or different approaches like bagging and boosting. 
Now, let’s have a look at why we need feature engineering in machine learning.

 

Importance of Feature Engineering
Feature engineering is a very important step in machine learning. Feature engineering refers to the process of designing artificial features into an algorithm. These artificial features are then used by that algorithm in order to improve its performance, or in other words, reap better results. Data scientists spend most of their time with data, and it becomes important to make models accurate.

Time spent by data scientist pie chart. 
Time spent by data scientist pie chart. | Image: Harshil Patel
When feature engineering activities are done correctly, the resulting data set is optimal and contains all of the important factors that affect the business problem. As a result of these data sets, the most accurate predictive models and the most useful insights are produced.

 

## Feature Engineering Techniques for Machine Learning
Lets review a few feature engineering best techniques that you can use. Some of the techniques listed may work better with certain algorithms or data sets, while others may be useful in all situations.
 

1. Imputation
Missing values are one of the most common issues you’ll come across when it comes to preparing your data for machine learning. Human error, data flow interruptions, privacy concerns and other factors could all contribute to missing values. Missing values have an impact on the performance of machine learning models. The main goal of imputation is to handle these missing values. There are two types of imputation:

- Numerical imputation.
- Categorical imputation.

a. Numerical Imputation 
To figure out what numbers should be assigned to people currently in the population, we usually use data from completed surveys or censuses. These data sets can include information about how many people eat different types of food, whether they live in a city or country with a cold climate and how much they earn every year. That is why numerical imputation is used to fill gaps in surveys or censuses when certain pieces of information are missing.

```
#Filling all missing values with 0
data = data.fillna(0)
```

b. Categorical Imputation 
When dealing with categorical columns, replacing missing values with the highest value in the column is a smart solution. However, if you believe the values in the column are evenly distributed and there is no dominating value, imputing a category like “Other” would be a better choice, as your imputation is more likely to converge to a random selection in this scenario.

```
#Max fill function for categorical columns
data[‘column_name’].fillna(data[‘column_name’].value_counts().idxmax(), inplace=True)
 ```

2. Handling Outliers
Outlier handling is a technique for removing outliers from a data set. This method can be used on a variety of scales to produce a more accurate data representation. This has an impact on the model’s performance. Depending on the model, the effect could be large or minimal. For example, linear regression is particularly susceptible to outliers. This procedure should be completed prior to model training. The various methods of handling outliers include:

- Removal: Outlier-containing entries are deleted from the distribution. However, if there are outliers across numerous variables, this strategy may result in a big chunk of the datasheet being missed.
- Replacing values: Alternatively, the outliers could be handled as missing values and replaced with suitable imputation.
- Capping: Using an arbitrary value or a value from a variable distribution to replace the maximum and minimum values.
- Discretization : Discretization is the process of converting continuous variables, models, and functions into discrete ones. This is accomplished by constructing a series of continuous intervals (or bins) that span the range of our desired variable/model/function.
 

3. Log Transform
Log transform is the most used technique among data scientists. It’s mostly used to turn a skewed distribution into a normal or less-skewed distribution. We take the log of the values in a column and utilize those values as the column in this transform. It’s used to handle confusing data, and the data becomes more approximative to normal applications.

```
//Log Example
df[log_price] = np.log(df[‘Price’])
 ```

4. One-Hot Encoding
A one-hot encoding is a type of encoding in which an element of a finite set is represented by the index in that set, where only one element has its index set to “1” and all other elements are assigned indices within the range [0, n-1]. In contrast to binary encoding schemes, where each bit can represent two values (i.e. 0 and 1), this scheme assigns a unique value for each possible case.

 

5. Scaling
Feature scaling is one of the most pervasive and difficult problems in machine learning, yet it’s one of the most important things to get right. In order to train a predictive model, we need data with a known set of features that needs to be scaled up or down as appropriate. After a scaling operation, the continuous features become similar in terms of range. Although this step isn’t required for many algorithms, it’s still a good idea to do so. Distance-based algorithms like k-nearest neighbor and k-means, on the other hand, require scaled continuous features as model input. There are two common ways for scaling:

- a. Normalization 
All values are scaled in a specified range between 0 and 1 via normalization (or min-max normalization). This modification has no influence on the feature’s distribution, however, it does exacerbate the effects of outliers due to lower standard deviations. As a result, it’s advised that outliers be dealt with prior to normalization.

- b. Standardization 
Standardization, or z-score normalization, is the process of scaling values while accounting for standard deviation. If the standard deviation of features differs, the range of those features will differ. The effect of outliers in the characteristics is reduced as a result. To arrive at a distribution with a 0 mean and 1 variance, all the data points are subtracted by their mean and the result divided by the distribution’s variance.


### Cateorical Encoding Techniques 
a. Traditional techniques - One hot encoding, count/frequency encoding and original/label encoding 

b. Monotonic relationship - Ordered label encoding, Mean encoding, Weight of evidence 

c. Alternative techniques - Binary encoding, Feature hashing 

