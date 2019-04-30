# Car Sales - EDA
![image1](/UkraineCarFleetSales/images/carfleet.png)
### DATA
- The Data set contains features/specifications of different branded cars in __Ukraine Car Fleet__
- Dataset contains __9576 entries and 10 columns/variables__
- __4__ Numeric and __6__ Categorical variables<br>
### ATTRIBUTE INFORMATION
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
### DATA CLEANSING
![image2](/UkraineCarFleetSales/images/cleansed_data1.png)<br><br/>
- Data is not always good to us, hence when we get __RAW/UNORGANIZED DATA__, we have to cleanse it removing bad characters, missing values, dropping duplicates and make it an __ORGANIZED DATA__
- __Python Pandas__ makes the job easy for us
### DATA IN DEPTH(after cleansing)
- Number of Entries: 9463
- Number of Variables: 12
- Numeric Variables: 5
- Categorical Variables: 7
- Extended Variables: 2
- Size in Memory: 887.2 kiB
### PROBLEM STATEMENT
#### Generally, by understanding all the specifications of car, we identify relationships among features and how they effect price/cost of car so that the fleet manager can make a decision of how many more cars and of what model as per budget he has to buy and maintain the fleet to grow.
#### EDA also identifies top used cars and their details in the fleet<br>
### EDA

