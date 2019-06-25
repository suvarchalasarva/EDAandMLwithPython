- This dataset was scraped from __Five Thirty Eight-Candy__ Power Ranking Dataset.
- It is collection  of multiple candies records with specifications like flavors(chocolate,caramel,peanutyalmondy,etc), sugar percent   contained them
- Data was collected by creating a website where participants were shown presenting two fun-sized candies and asked to click on the one they would prefer to receive. In total, more than __269 thousand votes__ were collected from 8,371 different IP addresses.
- Dataset contains __85__ entries and __13__ columns/variables
- __3__ Numeric , __1__ Categorical and __9__ Boolean variables<br>
- The Data is collected from mobile apps that use Insaid Telecom services. Full recognition and consent from individual user of those     apps have been obtained, and appropriate anonymization have been performed to protect privacy. 
- The data schema consists of follwing three tables.
- gender_age_train: Devices and their respective user gender, age and age_group
- Shape of gender_age_train is 74645 rows x 4 columns
- phone_brand_device_model: device ids, brand, and models phone_brand: note that few brands are in Chinese
- Shape of phone_device_model is 87726 rows X 3 columns
- events_data: when a user uses mobile on Mr. XY Telecom network, the event gets logged in this data.
- Each event has an event id, location (lat/long), and the event corresponds to frequency of mobile usage.
- Shape of events_data when filtered for our respective states “Madhya Pradesh, Goa, Chhattisgarh, Nagaland, Null and Uttaranchal” is     261472 rows X 7 columns
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
