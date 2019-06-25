# Consulting assignment on Telecom Service Provider
## SOURCE OF DATA 
![image1.png](images/halloweencandies.png)<br><br>
- The Data is collected from mobile apps that use Mr. XY Telecom services. Full recognition and consent from individual user of those       apps have been obtained, and appropriate anonymization have been performed to protect privacy. 
- The data schema consists of follwing three tables.
- __gender_age_train__: Devices and their respective user gender, age and age_group
- Shape of gender_age_train is 74645 rows x 4 columns
- __phone_brand_device_model__: device ids, brand, and models phone_brand: note that few brands are in Chinese
- Shape of phone_device_model is 87726 rows X 3 columns
- __events_data__: when a user uses mobile on Mr. XY Telecom network, the event gets logged in this data.
- Each event has an event id, location (lat/long), and the event corresponds to frequency of mobile usage.
- Shape of events_data when filtered for our respective states “Madhya Pradesh, Goa, Chhattisgarh, Nagaland, Null and Uttaranchal” is     261472 rows X 7 columns
## ATTRIBUTE INFORMATION
| Column Name   			| Description                                              		  |
| ------------- 			| --------------------------------------------------------------|                                            		
| age                    | age of user                                   	  | 
| gender        		| gender of user                     				        |  
| device_id          		| Unique id of device belonging to user                                         | 
| age_group       			| age_group of user      							            |                                            
| phone_brand       | Name of phone brand that user is using            |   
| device_model       				| Name of device_model that user is using                                      	|
| event_id 		| Event id of user using mobile at a single instance   |
| Latitude          			| Location column that is latitude value of user’s location when using mobile                       |
| Longitude          				| Location column that is longitude value of user’s location when using mobile                 |
| Timestamp    				| When user is using mobile                   |
| City				| Where user is using mobile 	|
| State 				| Where user is using mobile	|<br>
## DATA WRANGLING
- Fetched 'Null' state records from database.
- Based on device_id, updated state, latitude,longitude,city columns appropriately without discrepancies. 
- Checked for latitude and longitude containing "0" values and updated them with appropriate values based on device_id.
- Checked for incorrect values for latitude and longitude, updated them with correct values based on device_id.
- Fetched device_id containing value 0 records and updated them by latitude,longitude values. 
- Merged gender_age dataframe and events_ data dataframe and found no null records.
- Merged phone_brand_device_model dataframe with already above merged dataframe.
- There are NaN's for phone_brand,device_model columns in merged dataframe.
- These NaN's are filled by mode values from merged dataframe.
## PROBLEM STATEMENT
- To help the customer, the consultants are expected to have depth of clarity in the underlying data. Do help the service provider understand what the right way forward is and suggest actionable insights from marketing and product terms.
## PROBLEM ANALYSIS - EDA