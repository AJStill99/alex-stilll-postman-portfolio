# alex-stilll-postman-portfolio
This repository contains a **beginner-level API testing project using Postman**, created to demonstrate fundamental API testing concepts from a QA Engineer perspective.

The goal of this project is to show a clear understanding of how APIs work, how to send requests, and how to validate responses using simple, readable tests. It intentionally avoids over-engineering.

---

## Project Focus

This project focuses on:

- Understanding HTTP requests and responses  
- Validating API behaviour using Postman tests  
- Writing simple automated checks  
- Applying QA thinking to positive and negative scenarios  

This is a learning-focused project designed to complement a broader QA automation portfolio.

---

## API Used

**JSONPlaceholder**  
A public, fake REST API commonly used for learning and testing.

> **Note:**  
> JSONPlaceholder does not persist data.  
> POST, PATCH, and DELETE requests always return successful responses, even when data is invalid.  
> This behaviour is expected and documented.

---

## Requests Covered

The Postman collection includes the following requests:

- **GET Users**  
  Retrieve a list of users (positive scenario)

- **GET User Not Found**  
  Validate correct handling of a 404 response (negative scenario)

- **POST Create User**  
  Validate a successful creation response

- **PATCH Update User**  
  Validate partial update behaviour and response content

- **DELETE User**  
  Validate expected delete response status codes

---

## Testing Approach

Each request includes **post-response tests** written in JavaScript to validate:

- HTTP status codes  
- Presence of expected fields in the response  
- Basic response structure  

These tests are written as lightweight QA checks, similar to simple test cases.

---

## Tools Used

- Postman  
- JavaScript (Postman test scripts)
- GitHub

---

## Purpose

This project exists to demonstrate:

- API testing fundamentals  
- Clear and intentional test coverage  
- Beginner-level QA reasoning and validation  

It is intended to complement my Playwright UI automation portfolio.


