# MuleSoft Integration Projects

### App1 - Introductory Hello APP - emp-sapi.
### App2 - Test Flows, SubFlows & private Flows with Sync and Async functionality - test-flows.
### App3 - Playing with Oracle DataBase- CRUD Operations - emp-sapi-v1.
* Add Employee
* Delete Employee
* Fetch Employee by ID
* Fetch all the Employees
### App4 - Playing with JMS Connector Operations with ActiveMQ Queue and Topic - jms-app.
### App5 - Playing with JMS Connector Operations with ActiveMQ pushing and reading from a Queue - jms-push-operations.
### App6 - Playing with FTP Connector Operations with VSFTP by reading data from csv - ftp-app.
### App7 - Playing with FTP Connector Operations with VSFTP by dumping data from database to an excel file - database-to-ftp-excel.
### App8 - Playing with FILE Connector Operations by dumping data from a csv file to database in bulk using a Schedulor  - emp-csv-database.
### App9 - Playing with REST Request Connector by dumping data from one REST service to another REST Service  - consume-json-rest-service.
### App10 -rest-over-jms
* Playing with JMS Connector by dumping data from one ActiveMQ JMS Queue to a another REST Service which updates employee data using xml payload
* Cosuming Rest Service to delete an Employee using URI Parameters by using Choice
### App11 - Using per environment property file for deployment to a particular environment - prop-demo
### App12 - Using per environment property file for deployment to a particular environment using Mule Secure Configuration Module - secure-prop-demo
* hiding passwords of different connector configuration using a key
### App13 - Demonstrating Error handling when Business Requirements are not fullfilled: - error-handling-demo.
* On Error Propogate
* On Error Continue
* Raise Error
* Error Handler for a project
### APP14 - RAML Specification for a project - emp-onboard-sapi.raml
### APP15 - Mule Project made from RAML Specification - emp-onboard-api
* Global Connector Configurations
* Global Error Handler
* APIkit Router
* Separate Implementation Modules per call type using Flow references
### APP16 - Fragfmented RAML Specification for a project -emp-hr-sapi
### APP17 - Sample Provider SOAP Service - soap-service
* The difference compared to REST service is that rather than using apikit router we use soap router
### APP18 - Sample Consumer SOAP Service - ws-consumer-demo
* We are consuming a soap service and applying transformation on the final result
### APP19 - DataWeave Operations
* DW-Time-Conversions
* DW-Operators
* DW-DataTypes & Variables
* DW-Type-Coercions
* DW-Inbuilt-Functions
	* Math Functions
	* String Functions
	* Size of functions
* DW-UserDefined-Functions
* DW- Map, Map Object, Filter & Filter Object functions.
### APP20- Mule's Scopes - mule-scope-demo
* Target Scope .
* Aysnc Scope.
* Try/Catch scope.
	* with on error continue.
	* with on error propogate.
* Until Scope.
* ForEach Batch Processing (Synchronous with the main flow)
	* Scatter-Gather insert for multiple tables;
	* Bulk inserts using Batch option of foreach 
* Batch Job Connector processing (Asynchronous with the main flow)
	* Using Batch Step with only processor.
	* Using Batch Step with prcessor and Aggregator(Streaming or aggregator size).

####  REST Codes : https://www.restapitutorial.com/httpstatuscodes.html
