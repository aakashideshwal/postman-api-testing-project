# API Testing Project using Postman & Newman

## Project Overview

This project demonstrates automated API testing using Postman and Newman.
It includes testing of REST APIs with CRUD operations (GET, POST, PUT, DELETE) and automated test execution with HTML reporting.

## Tools & Technologies

* Postman (API Testing)
* Newman (CLI Automation)
* Node.js
* JSONPlaceholder API
* JavaScript (Postman Test Scripts)

## APIs Tested

* GET /users (Fetch user details)
* POST /users (Create new user)
* PUT /users/{id} (Update user)
* DELETE /users/{id} (Delete user)

## Test Validations Performed

* Status Code Validation (200, 201)
* Response Time Validation
* JSON Response Validation
* Schema & Field Validation
* Header Validation (Content-Type)
* Data Validation (name, job, id)

## Automation using Newman

* Executed Postman collection via Newman CLI
* Generated automated HTML test reports
* Command used:

```bash
newman run api-testing-collection.json -e environment.json -r htmlextra
```

## Test Report

HTML report generated using Newman reporter (htmlextra) for detailed execution results.

## Resume Value

This project showcases real-world API automation testing skills using Postman, Newman, and JavaScript assertions, aligned with industry QA practices.

## Author
**Aakashi Deshwal**  
Manual QA | Test Automation Beginner
