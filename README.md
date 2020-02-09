# PySpark_Streaming_App

This Spark streaming application processes fire hotspots data and weather data from 3 Kafka producers every 10 seconds, 
apply geo-hashing algorithm to evaluate location of hotspots, store locations of hotspots with the same geohash and weather details together, and finally write results to MongoDB. 

## Libraries used

1.	PySpark
2.	PyMongo
3.	Geohash
4.  time
5.  json
6.  os
