# Car Sales - EDA
![image1](/UkraineCarFleetSales/images/carfleet.png)
## DATA
- The Data set contains features/specifications of different branded cars in __Ukraine Car Fleet__
- Dataset contains __9576 entries and 10 columns/variables__
- __4__ Numeric and __6__ Categorical variables<br>
## ATTRIBUTE INFORMATION
| Column Name   | Description                                               |
| ------------- | -------------                                             | 
| Car           | Make/Manufacturer of car                                  | 
| Price         | Selling Price of Car(measured in USD)                     |  
| Body          | Body of Car                                               | 
| Mileage       | Mileage given by Car(dis travelled per qty of fuel)       |                                            
| engV          | Engine Volume of car(measured in c.c)                     |   
| engType       | Engine Type of car                                        |
| Registration  | Whether the car is registered or not                      |
| Year          | Manufacturing year of car                                 |
| Model         | Model of car                                              |
| Drive Type    | Drive Type of car                                         |<br>
## DATA CLEANSING
![image2](/UkraineCarFleetSales/images/cleansed_data1.png)<br><br/>
- Data is not always good to us, hence when we get __RAW/UNORGANIZED DATA__, we have to cleanse it removing bad characters, missing values, dropping duplicates and make it an __ORGANIZED DATA__
- __Python Pandas__ makes the job easy for us
## DATA IN DEPTH(after cleansing)
- Number of Entries: __9463__
- Number of Variables: __12__
- Numeric Variables: __5__
- Categorical Variables: __7__
- Extended Variables: __2__
- Size in Memory: __887.2 kiB__
## PROBLEM STATEMENT
#### Generally, by understanding all the specifications of car, we identify relationships among features and how they effect price/cost of car so that the fleet manager can make a decision of how many more cars and of what model as per budget he has to buy and maintain the fleet to grow.
#### EDA also identifies top used cars and their details in the fleet<br>
## EDA
![image3](/UkraineCarFleetSales/images/carcount.png)<br>
![image4](/UkraineCarFleetSales/images/pricevsyear.png)<br>
![image5](/UkraineCarFleetSales/images/topmodels_volks.png)<br>
![image6](/UkraineCarFleetSales/images/corr.png)<br>
## INSIGHTS
#### Below are few insights
- The __Volkswagen__ manufacturer cars and models are __most available registered__ cars in the Ukraine Car Fleet.
- __Price__ of car is effected by parameters like __Engine Type, Engine Volume, Body Type, Manufacturing year__ ,etc.
- Studying all the features and their effect on parameters helps Ukraine Fleet Manager in making decision of what brand, new/used cars they have to maintain in order to grow the fleet and make it a big Car Fleet in Ukraine
