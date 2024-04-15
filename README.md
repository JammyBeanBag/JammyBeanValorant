# About

This is my solo passion project to track matches for myself and some other players so that I can visualize my performance over time. 
My program leverages Henrik's Valorant API to retrieve match information such as eliminations, ability usage, locations, and much more. 

JammyBeanValorant is specifically tasked with updating every registered player with their most recent matches and uploading those to my databases for caching. 

pyMongoValorant queries the mongoDB and creates some visualizations based on the data produced from those queries. 

# Database

I currently utilize two databases, one using MariaDB (SQL) and the other using MongoDB. Both of these databases I manage myself and are private collections. 

# Credits

You can visit Henrik's github at https://github.com/Henrik-3/unofficial-valorant-api

I also utilize https://valorant-api.com/ for most of the image work done. 

Special thanks to both of them, as this project would not be possible without their help. 
