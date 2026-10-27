# REST API Testing Portfolio — Postman

## Overview

A hands-on REST API testing project built with Postman and JavaScript, using JSONPlaceholder as the API under test.

This project demonstrates functional API testing, positive and negative scenarios, response validation, reusable test assertions, and structured QA reporting.

## API Under Test

**JSONPlaceholder:** https://jsonplaceholder.typicode.com

JSONPlaceholder is a public mock REST API intended for testing and demonstration.

## Tools & Technologies

- **Postman** — API requests and test execution
- **JavaScript** — reusable test assertions
- **REST API** — HTTP methods and response validation
- **JSON** — request and response data
- **Excel** — test cases and execution results
- **QA documentation** — test report and execution evidence

## Test Coverage

The project covers nine API testing scenarios:

| Test ID | Scenario | Method |
|---|---|---|
| TC-API-001 | Retrieve a single post | GET |
| TC-API-002 | Retrieve all posts | GET |
| TC-API-003 | Retrieve a nonexistent post | GET |
| TC-API-004 | Create a post with valid data | POST |
| TC-API-005 | Create a post without a title | POST |
| TC-API-006 | Update a post | PUT |
| TC-API-007 | Partially update a post | PATCH |
| TC-API-008 | Delete an existing post | DELETE |
| TC-API-009 | Delete a nonexistent post | DELETE |

### Validation Areas

- HTTP status codes
- JSON response structure
- Required fields and data types
- Response values and updated fields
- Positive and negative scenarios
- Basic response-time checks
- Reusable JavaScript assertions

## Project Structure

- `01 Postman Collection/` — exported Postman collection
- `02 Test Cases & Results/` — Excel test cases and results
- `03 Screenshots/` — selected request and test execution evidence
- `04 QA Report/` — final QA report in PDF and DOCX formats
- `REST API Testing Portfolio Showcase.png` — portfolio overview image

## Results

**Final reported status: 9/9 test scenarios passed.**

The project covers the nine scenarios listed above. The Excel workbook and QA report provide supporting test documentation and execution evidence.

Individual assertion totals are not reported here because a consolidated assertion count has not been established.

## How to Run

1. Open Postman and import `API_Testing_Portfolio.postman_collection.json` from `01 Postman Collection/`.
2. Configure the environment variable `base_url` with the value `https://jsonplaceholder.typicode.com`.
3. Select the correct environment.
4. Run individual requests or execute the collection using the Collection Runner.
5. Review the **Test Results** tab and compare the results with the Excel test-case report.

## Important Limitation

JSONPlaceholder is a mock API. Write operations such as POST, PUT, PATCH, and DELETE are simulated and are not permanently persisted.

The results demonstrate the behavior of this test service and should not be interpreted as proof of production API behavior.

## Deliverables

- Importable Postman collection
- Nine documented API test scenarios
- Excel test-case and results workbook
- Screenshots of selected test executions
- Final QA report in PDF and DOCX formats

## Project Purpose

This portfolio project demonstrates practical API testing skills, test design, JavaScript assertions, response validation, and QA documentation relevant to software testing and test automation roles.
