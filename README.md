Jaago
=====

Specification:
The application aims to provide momentum to social movements/struggles by raising public awareness by providing a platform for people to contribute to social causes by organizing events. It serves as a database for people to find the causes they most identify with.

Design:
This social awareness app is a hybrid application since it runs on an Android Device but uses an external database hosted on a linux server over the World Wide Web to fetch the data to display to the end-user. We contact a server URL, which upon visiting runs an SQL query over a database, and returns a JSON object to the application which is then parsed and displayed accordingly. Our application recognizes the social movements/struggles as 'Causes'. We have a central server from which our application fetches the data. All the data is stored in a database using MySQL. We fetch the data by calling PHP pages on web browsers that returns the information as JSON objects. With each cause, any logged in user has the ability to create events. The event functionality allows users to meet and discuss about these movements/struggles.

OS/API Details:
1. Android API Minimum Level -10
2. Linux Operating System running the LAMP stack

Note: LAMP stack stands for :
'L'inux - operating system
'A'pache - HTTP server
'M'ySQL - database management system
'P'HP - scripting language

