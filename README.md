Wine-quality-data-Visualization

I have used Wine Dataset from UCI repository.The dataset is in two parts, white and red wine.
The attributes in the dataset are as mentioned below.

Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)

After merging the two datasets I have created two new variables, wine typeto indicate whether the wine is red or white and quality. 
For quality label – I grouped the quality level as low if it is below 5, medium if its between 5-7 and high if it is above 7.
