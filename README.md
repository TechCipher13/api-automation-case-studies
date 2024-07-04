# API Automation with Postman

## Project Overview

This project is focused on automating the testing of a booking API using Postman. The automated tests cover the following functionalities:
- Create Booking
- Get Booking by ID
- Update Booking
- Delete Booking

The tests include both positive scenarios (with valid input data) and validation scenarios (with invalid input data).

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [Newman](https://www.npmjs.com/package/newman)
- [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/api-automation-case-studies.git
    cd api-automation-case-studies
    ```

2. Install Newman and the HTML Extra Reporter:

    ```bash
    npm install -g newman
    npm install -g newman-reporter-htmlextra
    ```

## Running the Tests

### Using Newman

To run the tests using Newman and generate an HTML report, use the following command:

```bash
newman run <your-postman-collection-file>.json -r htmlextra
```

## Execution Report

Upon executing the tests, you will receive a detailed report summarizing the test results. Below is an example of a report generated from the test execution:

![Execution Report](https://github.com/TechCipher13/web-automation-case-studies/blob/main/HTMLReport.png)
