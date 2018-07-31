# Lagom-starter
   A sample lagom code which will be a good starting point.
####  What is Lagom framework? 

  Lagom is an open source framework for building reactive microservice systems in Java or Scala.
	
	https://www.lagomframework.com/

#### **What the code does ?**
Sample code downloads  bulk weather data from [http://bulk.openweathermap.org/sample/]( http://bulk.openweathermap.org/sample/) and updates local cassandra db which can be used to provide weather details offline.

It uses  AKKA and KAFKA which provides high scalability.High level of parallelism provides faster completion of process.

It processes 10 MB of weather data in fraction of seconds.

![Data processing](/screenshot/int.PNG)

#### Getting Started

command to start Lagom : ** mvn lagom:runAll **

Screen Shots ::

###### LAGOM Gateway


![LAGOM Gateway](/screenshot/Gateway.PNG)

###### LAGOM Stared

![LAGOM Stared](/screenshot/lagomLog.PNG)


###### Casandra 

![Casandra](/screenshot/Casandra1.PNG)

###### Casandra 

![Casandra](/screenshot/Casandra2.PNG)

###### Casandra 

![Casandra](/screenshot/Casandra3.PNG)