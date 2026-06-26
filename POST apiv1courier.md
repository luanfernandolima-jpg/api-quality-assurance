# API Endpoints

## Create Courier

**Method:** `POST`

**Endpoint:** `/api/v1/courier`

## Courier Login

**Method:** `POST`

**Endpoint:** `/api/v1/courier/login`

## Delete Courier

**Method:** `DELETE`

**Endpoint:** `/api/v1/courier/:id`

---

## Test Scope

The following validations were performed:

* Required field validation
* Minimum and maximum field length
* Invalid data validation
* Empty field validation
* Duplicate data validation
* Business rule validation
* Positive scenarios
* Negative scenarios
* Boundary Value Analysis (BVA)

## Test Cases

The project includes test scenarios covering:

* Valid requests
* Invalid requests
* Missing required fields
* Fields below the minimum length
* Fields above the maximum length
* Invalid data formats
* Duplicate records
* Business rule validation

## Expected Results

* Valid requests should return the expected success response.
* Invalid requests should return the appropriate HTTP status code and validation messages.
* All business rules should be enforced consistently.

## Bug Reports

The defects identified during testing were documented separately using standard bug reporting practices.

## Tools Used

* Postman
* Microsoft Excel
* Jira
* Git
* GitHub
