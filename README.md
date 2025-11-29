# API Testing Project 2 – Petstore Orders (Postman)

## Overview
This project contains manual API testing for Swagger Petstore **Store / Order** endpoints using Postman.  
Tested CRUD operations, validations, and positive/negative scenarios.

## Tools Used
- Postman
- Newman (optional)
- JSON

## What I Tested
- **Create Order** (POST)
- **Get Order by ID** (GET)
- **Delete Order** (DELETE)
- Response validation: status codes, body, headers, response time
- Positive and negative test cases
- Environment & collection variables

## How to Run (Newman)
```bash
newman run "Petstore Orders.postman_collection.json" -e "Pet_store.postman_environment.json" -r cli,html
