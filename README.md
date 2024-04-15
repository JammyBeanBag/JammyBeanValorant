# Tracking

This is my solo passion project to track matches for myself and some other players so that I can visualize my performance over time. 
At the moment, we make use of Henrik's API. 
You can visit their github at https://github.com/Henrik-3/unofficial-valorant-api

We also utilize https://valorant-api.com/
Special thanks to both of them, as this project would not be possible without their help. 

# Function
Valorant Tracking is specifically tasked with updating every registered player with their most recent matches and uploading those to my databases for caching. 
pyMongoValorant queries the mongoDB and creates some visualizations based on the data produced from those queries. 

# Database
I currently utilize two databases, one using MariaDB (SQL) and the other using MongoDB. Both of these databases I manage myself and are private collections. 
