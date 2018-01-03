TIMO - Update Microservice
========================

Webservice that checks if there are updates and performs them on the microservices and the arduino

# How to Check for Updates

# How an Update Works
1. Update Repositories locally using git pull
2. Update Database-Files if needed
3. Compile Arduino-Code and send it
4. restart apps using pm2

# API
* GET / <- returns if an update is nedded
* POST /check <- Force Check for Updates

# TODO
* Add raml for api
* code routes
* lib update
* how to check
* build script (testresults into html)