Analysis of Ford GoBike System Data
by Abiodun Mohammed
Dataset
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv

The Data consists of 13 variables and includes:

Trip Duration (seconds)
Start Time and Date
End Time and Date
Start Station ID
Start Station Name
Start Station Latitude
Start Station Longitude
End Station ID
End Station Name
End Station Latitude
End Station Longitude
Bike ID
User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
Some of the data wrangling steps carried out during the analysis involves and not limited to change of dtype of some columns, creating a new column from previous one, and removing irrelevant columns as well as rows with missing entries.

Summary of Findings
In the exploration, I found that there was a strong relationship between the ages and duration in seconds of trips, user type and member gender. The relationship is approximately linear between age and duration in seconds when duration in seconds is transformed to be on a logarithmic scale. I found a somewhat not surprising result initially when the marginal trend for the longer trips duration and member data base both customer and subscribers were donminated by the male gender. However, customer user type accounts for longer average duration in seconds despite accounting for 9.4% of the total user.

Key Insights for Presentation
The casual users travel twice more than their clients in average duration of trips in seconds. Ages between 28 and 40 are more interested in Riding Bike
