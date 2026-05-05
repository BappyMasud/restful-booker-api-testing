# Restful Booker API Testing Project

## Project Overview

This project demonstrates API testing of the Restful Booker application using Postman and Newman. It includes automated tests for CRUD operations and authentication.

---

## Test Scenarios Covered

* Get Booking IDs
* Create Booking
* Get Booking Details
* Generate Auth Token
* Update Booking (PUT)
* Partial Update (PATCH)
* Delete Booking

---

## Validations Implemented

* Status Code Validation
* Response Body Validation
* Data Type Validation
* Response Time Validation
* JSON Structure Validation
* Environment Variable Handling

---

## Tools & Technologies

* Postman
* Newman
* Node.js

---

## Project Structure

```
restful-booker-api-testing/
│
├── collection/
│   └── Restful_Booker_collection.json
│
├── environment/
│   └── Restful_Booker_environment.json
│
├── test-results/
│
├── package.json
├── README.md
```

---

## How to Run the Project

### 1️⃣ Install Dependencies

```bash
npm install
```

---

### 2️⃣ Run API Tests

```bash
npm test
```

---

### 3️⃣ Generate HTML Report

```bash
npm run report
```

Report will be generated in:

```
test-results/report.html
```

---

## Features

* Automated API Testing
* Dynamic Data Handling (bookingId, token)
* End-to-End Test Flow
* HTML Reporting

---

## Author

**Bappy Masud**

---

## Notes

This project is created for learning and demonstrating API testing skills for Software QA roles.
