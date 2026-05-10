# API Testing Project – Restful Booker

This project contains API test automation for the Restful Booker API using Postman and Newman.

## Project Overview

The goal of this project is to perform end-to-end API testing on the Restful Booker API by validating booking workflows including Create, Read, Update, Partial Update, Authentication, and Delete operations.

## Tested Modules

- Create Booking
- Get Booking
- Authentication
- Update Booking
- Get Booking Copy
- Partial Update Booking
- Get Booking Copy 2
- Delete Booking
- Get Booking Copy 3

## Tools & Technologies

- Postman
- Newman
- Newman HTML Extra Reporter
- JavaScript
- REST API Testing

## Key Testing Features

- Dynamic data generation using pre-request scripts
- Environment variable handling
- Response assertions and validations
- Token-based authentication testing
- CRUD operation testing
- Test chaining between requests
- Automated HTML report generation

## Project Structure

```bash
├── Collection.json
├── Environment.json
├── Reports/
└── README.md
```

## How to Run

### Clone Repository

```bash
git clone <your-repo-link>
cd <project-folder>
```

### Install Newman

```bash
npm install -g newman
```

### Install HTML Extra Reporter

```bash
npm install -g newman-reporter-htmlextra
```

### Run Collection

```bash
newman run Collection.json -e Environment.json
```

### Generate HTML Report

```bash
newman run Collection.json -e Environment.json -r htmlextra
```

## Assertions Covered

- Status code validation
- Response time validation
- Response schema validation
- Data integrity validation
- Authentication token validation

## API Documentation

[https://restful-booker.herokuapp.com/apidoc/index.html](https://documenter.getpostman.com/view/46928810/2sBXqNmJhN)

## Report Sample

HTML report generated using Newman HTML Extra Reporter.

## Author

Tahsin Ahmmed

QA Engineer | SQA Enthusiast | API Tester
<img width="1105" height="884" alt="report" src="https://github.com/user-attachments/assets/238da76d-2569-4d9f-92b2-b73a0f081e3a" />
<img width="1111" height="847" alt="report1" src="https://github.com/user-attachments/assets/bdd85985-f53a-4690-9e01-e2c6d378214d" />



