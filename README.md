# Leader_Keeper
Game Data Web App
Spring Boot CRUD application with RESTful API service using a MySQL database instance.

## Objectives  
These objectives are numbered by priority and implementation order.
1. Provide a API for authorized users to manage game data. 
2. Provide a frontend web page for authorized users to view and managage (create, read, update and delete) game data.

## How to Use Leader Keeper
### Running on Local Machine 
Prior to the service being hosted on a cloud platform (or any time desired) this application can be run locally.
#### Local Machine Prerequisites
1. The procedure for running on a local machine is written for a computer with  MySQL installed.
2. Download and unpack the zip from the project github repository.
#### Local Machine Procedure
Once the Frontend is ready, additional instructions will be added for local use.
1. Create a dedicated MySQL instance. 
2. Update the application.properties file found in the src/main/resources directory to connect to the MySQL instance just created.
3. From a terminal, navigate to the base directory of the project and start the CRUD API service with the command ./gradlew bootRun.
4. Once the CRUD API service is running, API calls implemented in the controller can be made from an API client like Postman or terminal tools like curl.
5. For now the application is terminated with ctrl-c from the terminal is was launched in.
### Using the hosted web app
A URL and basic instructions will be provided here once the frontend application is implemented and hosted on the web.
