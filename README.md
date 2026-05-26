# Fake Store API Testing with Postman

This project showcases API testing skills using Postman and Newman against the public practice API provided by:

https://fakestoreapi.com/

The collection includes testing for:

- GET requests
- POST requests
- PUT requests
- PATCH requests
- DELETE requests

## Important Note

`PUT`, `PATCH`, and `DELETE` requests on Fake Store API return successful responses and status codes for practice purposes, but they do **not actually make permanent changes** to the API data.

This API is intended for learning and testing workflows safely.

---

# Project Files

- `Products.postman_collection.json` → Postman collection containing API requests
- `Newman HTML Extra Report` → Attached execution report generated using Newman HTML Extra Reporter

---

# Tools Used

- Postman
- Newman
- Newman HTML Extra Reporter

---

# Requirements

Install:

- Newman
- Newman HTML Extra Reporter

---

# Run the Collection

Open terminal in the folder where the collection JSON file exists and run:

```bash
newman run Products.postman_collection.json -r htmlextra
```

---

# What This Project Demonstrates

- API testing using Postman
- Running collections with Newman
- Working with REST APIs
- Understanding HTTP methods and status codes
- Generating execution reports using HTML Extra Reporter
- Basic API testing workflow for portfolio/practice purposes

---

# API Base URL

```txt
https://fakestoreapi.com/
```

---

# Report

The attached HTML Extra report contains:

- Request execution details
- Response status codes
- Response times
- Execution summary
- Assertion results

---

# Purpose

This repository was created to showcase practical API testing skills using Postman, Newman, and automated report generation.


# Reports Screenshot

<img width="1096" height="862" alt="image" src="https://github.com/user-attachments/assets/1ec3c583-4fda-477e-aaf3-18709c6d1d5e" />
