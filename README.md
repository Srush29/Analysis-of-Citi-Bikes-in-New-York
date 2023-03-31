# Analysis of Citi Bikes in New York



                           
Introduction:
• NYC is the most populated city in the USA with over 8.8 million people
• In 2013, a shared bicycle system known as Citi Bike has been available
• The benefits include reducing dependence on automobiles and encouraging
public health through exercise
• The system has been expanding each year, with increases in the number of
bicycles available
• The usage data provides a wealth of information which can be mined
• With such intelligence, the company would be better positioned to determine
what actions might optimize its revenue stream

Data Gathering:
Making sure we are using the appropriate and proper amount of data was crucial because our project uses real-time generated data. To be sure we had a compiled dataset, we have taken a few steps. First, we took data files for the months of February through September in 2022. We got a total of 4.5M rows of this combined data for these months. After that, we sampled the combined data and prepared a dataset of 1,123,046 rows of data which is approximately 1.1M rows of data.

Goals:
Our goal is to explore the Citi Bike data and find insights to monitor the demand of Citi Bikes and analyze the trends. Some of the questions that we would like to answer are:
1. What are the most probable locations to take Citi Bike from?
2. What is the daily, monthly demand for Citi Bikes?
3. How is the Citi Bike trend on Weekends and Weekdays?
4. What is the average trip duration of Citi Bike rides?
            
Dataset description and attributes:
 
Column Name
Description
Index
rideable_type
ended_at
start_station_id
end_station_id
start_lng
end_lng
Index number
Type of bike (Electric, Classic, Docked)
Time and date the ride ended
Start station ID from where the ride started
End station name from where the ride ended: The longitude of the bike from where the ride started The longitude of the bike from where the ride ended
ride_id: Ride ID number
started_at: Time and date the ride started
start_station_name: Start station name from where the ride started
end_station_name: End station name from where the ride ended
start_lat: The latitude of the bike from when the ride started
end_lat: The latitude of the bike from when the ride ended
member_casual
Member ride or Casual ride
Official Citi Bike website: https://ride.citibikenyc.com/system-data Data ranges from February 2022 to September 2022
The dataset consists of 1,123,046 rows and 14 columns


