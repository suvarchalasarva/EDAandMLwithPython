# Exploratory Data Analysis <br>
## What is DATA?
##### DATA is facts or figures which can be collected,organized,interpreted,processed,structured to make meaningful information which provide insights for betterment of businesses<br>
## Why Exploratory Data Analysis(EDA)?
##### Everything around us is DATA. In order to understand DATA and make gainful insights, we need to understand it more and for that, we perform Exploratory Data Analysis(EDA) on it<br>
## what is EDA?
##### Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to 
      1. Discover patterns
      2. Spot anomalies
      3. Test hypothesis 
      4. Check assumptions with the help of summary statistics 
      5. Graphical representations<br>
![image1](/images/EDA.png)
# Machine Learning<br>
## What is Machine Learning?
#####  Artificial intelligence(AI) is the broad science of mimicking human abilities, machine learning is a specific subset of AI that trains a machine how to learn, identify patterns and make decisions with minimal human intervention.<br>
![image4](/images/MachineLearning)<br><br>
##### Machine Learning is the science of getting computers to act(make predictions on data) without being explicitly programmed
##### It is one of the exciting technologies that one would come across, actively being used, perhaps in many more places than one would expect like predicting weather, sales per month/year of any product, recommendation engines(amazon,e-commerce sites),Email spam detections,credit card fraud detections, banking sector,voice recognition, speech recognition(Alexa,Cortona,Siri) etc., and many more...<br>
##### Machine Learning Models learn form data, looks for patterns, build model and predict reliable outcomes which further help businesses in making decisions through its powerful insights<br>
## Machine Learning Process
![image5](/images/machinelearningprocess.png)<br><br>
## Repository Overview
##### This Repository is about EDA on datsets and machine learning models build on datasets using python<br>
## Table of Contents
* [Ukraine Car Fleet Sales](#section1)<br>
* [Halloween Candies Winpercent](#section2)<br>
________________________________________________________________________________________________________________________________________

<a id="section1"></a>
### [Ukraine Car Fleet Sales-EDA](./UkraineCarFleetSales)
![image2](/images/carsales.png)<br><br>
   - Proposed Dataset is collection  of multiple car records along with specifications that are available in the Ukraine Car Fleet
   - The purpose of this research(EDA) is to identify how Fleet can grow based on available cars specifictions and as well as car's
     maintenance costs 
   - EDA effort provides an insight of __Volkswagen__ Make Cars are mostly used and available registered cars in the Fleet 
   - EDA effort also identified relationships among specifications/features of the car so that the Manager of the Fleet is updated
     with insight of what type/featured cars they have to maintain in the Fleet to turn it to a big one 
   - [Link for Jupyter Notebook](./UkraineCarFleetSales/CarSalesProject.ipynb)
________________________________________________________________________________________________________________________________________

<a id="section2"></a>
### [Halloween Candy Winpercent Prediction](./HalloweenCandyWinpercent)
![image3](/images/c1.png)<br><br>
   - Proposed dataset was scraped from Five Thirty Eight-Candy Power Ranking and is collection of multiple candies records with
     specifications like flavors(chocolate,caramel,crispedricewafer),sugar percent contained in them
   - The purpose of this research(EDA) is to check what type/flavored candy is mostly liked/voted by people so that the candy makers
      can add those flavors and cutomize their candies in order to grow their sales
   - A model is built to predict __winpercent(people liking the taste of candy)__ of any flavored candy
   - EDA effort identified relationships among all flavors so as what combination of flavors are mostly liked by people
   - Model Prediction insight was such __chocolate flavored candies gain high winpercents__ compared to other features
   - [Link for Jupyter Notebook](./HalloweenCandyWinpercent/Candywinpercent.ipynb)
