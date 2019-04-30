# Car Sales - EDA
![image1](/UkraineCarFleetSales/images/carfleet.png)
### DATA
- The Data set contains features/specifications of different branded cars in Ukraine Car Fleet
- Dataset contains 9576 entries and 10 columns/variables
- 4 Numeric and 6 Categorical variables<br>
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
![image2](/UkraineCarFleetSales/images/cleansed_data.png)<br> 
- Data is not always good to us, hence when we get RAW/UNORGANIZED DATA, we have to cleanse it removing bad characters, missing values, dropping duplicates and make it ORGANIZED DATA
- Python Pandas allows us with different functions and makes the job easy
