# HALLOWEEN CANDY WINPERCENT
## DATA
![image1.png](images/halloweencandies.png)<br><br>
- This dataset was scraped from __Five Thirty Eight-Candy__ Power Ranking Dataset.
- It is collection  of multiple candies records with specifications like flavors(chocolate,caramel,peanutyalmondy,etc), sugar percent   contained them
- Data was collected by creating a website where participants were shown presenting two fun-sized candies and asked to click on the one they would prefer to receive. In total, more than __269 thousand votes__ were collected from 8,371 different IP addresses.
- Dataset contains __85__ entries and __13__ columns/variables
- __3__ Numeric , __1__ Categorical and __9__ Boolean variables<br>
## ATTRIBUTE INFORMATION
| Column Name   			| Description                                              		  |
| ------------- 			| --------------------------------------------------------------|                                            		
| competitor Name     | Name of competitor brand                                   	  | 
| chocolate        		| Does it contain chocolate?                     				        |  
| fruity          		| Is it fruit flavored?                                         | 
| caramel       			| Is there caramel in the candy?      							            |                                            
| peanutalmondy       | Does it contain peanuts, peanut butter or almonds?            |   
| nougat       				| Does it contain nougat?                                      	|
| crispedricewafer 		| Does it contain crisped rice, wafers, or a cookie component   |
| hard          			| Is it a hard candy?                                  			    |
| bar          				| Is it a candy bar?                                            |
| pluribus    				| Is it one of many candies in a bag or box?                    |
| sugarpercent				| The percentile of sugar it falls under within the data set  	|
| pricepercent 				| The unit price percentile compared to the rest of the set 	  |
| winpercent				  | The overall win percentage according to 269,000 matchups		  |<br>
## DATA IN DEPTH
- Number of Entries:     __85__
- Number of Variables:   __13__
- Numeric Variables:     __3__
- Categorical Variable:  __0__
- Boolean Variables:     __9__
- Text Variable:         __1__
- Size in Memory:      __8.7 KiB__
## PROBLEM STATEMENT
- What’s the best (or at least the most popular) Halloween candy(win percent)?
- Which specified features/columns are associated with higher rankings?
- Identify how each feature has effect on other features , study the correlations
- Generally, by studying insights from above will help candy manufacturers/makers know what type of flavor is mostly liked by people and they can include those flavors in their candies and make good business
## EDA
![image2.png](images/chocolatecount.png)
![image3.png](images/winpercentrange.png)
![image4.png](images/chocowinpercent.png)
![image5.png](images/peanutysugar.png)
![image6.png](images/peanutyprice.png)
![image7.png](images/peanutypairplot.png)
![image8.png](images/corr.png)<br>
## Using Predictive Modelling Technique(Linear Regression)
Our Dataset's target variable is __winpercent__ and is continuous numeric variable, so we use __Linear Regression Machine Learning Model__ to predict winpercent of __any flavored candy__ and __combination of different flavored candies__  
![image9.png](images/LR.png)
![image10.png](images/SLR.png)<br>
#### Studying the featured columns and interpreting their coefficients, we get to know how each feature is effecting the target variable __winpercent__
- __caramel,hard,bar,pluribus,crispedricewafer__ candies contribute to __low winpercents__ and hence we drop those features by studying metrics(as well as correlated variables)
- Before doing feature selection __RMSE__ for the test dataset was __12.252__
- After discarding __'hard','bar','caramel','pluribus','crispedricewafer'__ columns, RMSE comes to be __10.566__
![image10.png](images/regressioncurv.png)<br/>
## INSIGHTS
![image11.png](/images/insight.png)
- Top winpercent candies having high winpercent __84.180,81.866__ are __Reeses Peanut Butter, Reeses Miniature__ contain following flavors
     __chocolate, caramel,peanutyalmondy,not hard, not bar__ candies
- Least winpercent candies 22.44,23.41 are __Nik L Nip,Boston Baked Beans__ have following flavors
     __fruity,pluribus,peanutyalmondy__
- __chocolate, fuity, peanutyalmondy, nougat__ are Independent variables contributing to good winpercents
- Most of the __hard candies are not liked by people__, all hard candies are non bar candies have less winpercents
