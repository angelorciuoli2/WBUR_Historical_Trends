Context
WBUR-FM is a public radio station located in Boston, Massachusetts, owned by Boston University. Its programming is also known as WBUR News. Given the opportunity to work with their data, our collaborative goal was to understand the historical trends and extract insights from to inform WBUR’s event strategy, provide a set of visualizations that explore attendance and profit trends to help the WBUR team evaluate its performance. 

Data Sources and Transformations
There were 3 different data sources I used to conduct analysis on WBUR’s historical trends. 
CSV Original File Names: Event Attendance Data, Purchase Records, Transaction Details
Event Attendance transformations: 
Created category and genre column based on similarities in event title
Created guest_speaker column, where value is ‘Yes’ if guest’s name is included in the title of the event 
Purchase and Transaction transformations:
Removed rows with excessive null values
Merged datasets with corresponding ‘Order Id’ variables
Joined the merged datasets with attendance, to create a ‘Total_Profit’ and ‘Quantity Tickets’ to include the total profit and the number of tickets bought from each event in the attendance data
Final Data sources used in analysis (after transformations): 
Plot 1: 'Cityspace_Attendance_Updated.csv' → before merging purchase and transaction data
Plot 2 and 3: 'Cityspace_Attendance_with_Profits_Tickets.csv' → after merging purchase and transaction data
