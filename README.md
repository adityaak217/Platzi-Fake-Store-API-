# Project Overview
This project involves testing the Users Endpoint of the Platzi Fake Store API using Postman to ensure the proper functionality of the API. Both positive and negative test scenarios have been covered, and the results have been generated in a report using Newman, a command-line collection runner for Postman.

# API Information
- API Base URL: https://api.escuelajs.co/docs
- API Endpoint: /api/v1/users

# HTTP Methods Tested:
1. GET: Retrieve details of users.
2. POST: Create a new user.
3. PUT: Update an existing user's information.
4. DELETE: Remove a user from the database.

# Tools Used
- Postman: Used for API endpoint testing.
- Newman: Used to run the Postman collections and generate the test 

# Project Setup
- Clone the Repository: Open a terminal or command prompt. Clone the repository to your local machine using the following command:
```
git clone <repository-url>

```
- Import the Postman Collection: Open Postman. In Postman, click the Import button in the app.Upload the Postman collection file (API_Test_Collection.postman_collection.json), found in the repository. 




# Running the Collection with Newman 
To generate an HTML report using Newman, run the following command:
```
newman run "collection.json" -r htmlextra
```

