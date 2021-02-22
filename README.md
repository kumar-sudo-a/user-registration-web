# User registration web project

User Registration and Login 

This is a sample project which allows user to register and login to view all the registered users

Used Redux for State management

Implemented Function and Class components - Lifecycle Hooks

Used Alert Actions of type: SUCCESS, ERROR, CLEAR

Service - Handles all the API Responses and dispatches the events based on the Status Codes. Promise/Axios

200 - Ok (GET)

201 - Created (POST)

401 - Unauthorized

404 - Not Found



Login Page (POST request) - User can Login to the website if the registeration is successful and the API returns a 200 status code

Login Page USER NOT FOUND - If the User is not registered a 404 status code is returned and an alret is displayed showing that the User Not Found - Promise.reject.

Login Page PASSWORD INCORRECT - If the User enters a wrong password an Incorrect Password Alert is displayed - Promise.reject.