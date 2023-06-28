
# Elevator API
This project is a Spring Boot application that provides an API for controlling elevators in a building.

Endpoints
The following endpoints are available:

/callElevator - Call an elevator from one floor to another.
/getElevatorInfo - Get real-time information about an elevator, such as its current location, state, and direction.
/getLogs - Get a list of all events that have occurred, such as when an elevator was called, when it moved to a new floor, or when its doors opened or closed.
Requirements
The following requirements must be met in order to run the application:

Java 11
Maven
A database (MySQL or PostgreSQL)
Running the application
To run the application, you can use the following command:

mvn spring-boot:run

Code snippet

Once the application is running, you can access the API at the following URL:

http://localhost:8080/

Code snippet

## Testing the application

You can test the application by making requests to the endpoints using a tool like Postman.

## Logging

The application logs all events to a database. You can view the logs by visiting the following URL:

http://localhost:8080/logs

Unit testing
The application has unit tests that ensure that all of the code is working properly. To run the unit tests, you can use the following command:

mvn test

Contributing
If you would like to contribute to this project, please fork the repository https://github.com/cyrus43/Elevator-API and submit a pull request.

License
This project is licensed under the MIT License.

