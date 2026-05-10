# API Testing Project – Restful Booker

This project contains API test automation for the Restful Booker API using Postman and Newman.

## Project Overview

The goal of this project is to perform end-to-end API testing on the Restful Booker API by validating booking workflows including Create, Read, Update, Partial Update, Authentication, and Delete operations.

## Tested Modules

- Create Booking
- Get Booking
- Authentication
- Update Booking
- Partial Update Booking
- Delete Booking

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

Restful Booker API Documentation:
https://restful-booker.herokuapp.com/apidoc/index.html

## Report Sample

HTML report generated using Newman HTML Extra Reporter.

## Author

Tahsin Ahmmed

QA Engineer | SQA Enthusiast | API Tester
