PetStore API – Homework Week 5 (Postman Collection)

This Postman collection was created as part of QA automation practice and includes both positive and negative test cases for the PetStore API.

✅ Covered operations:
POST /pet – Create a new pet (valid, invalid, missing fields, missing auth)

GET /pet/{id} – Get pet by ID (valid and non-existing)

GET /pet/findByStatus – Get pets by status (e.g., available)

PUT /pet – Update existing pet (full and partial update)

DELETE /pet/{id} – Delete pet (existing and non-existing)

🔁 Automation elements included:
Pre-request Script: Generates a random pet name and sets it as a variable.

Tests (Post-scripts): Check response status, extract id into environment variable, validate error messages.

Environment Variables: Used for baseUrl, apiKey, petName, and createdPetID.

🔐 Authorization:
Uses API key (special-key) passed via headers.

Includes one negative test without authorization.

📌 Notes:
Collection includes a mix of happy path and edge cases (invalid data, repeated delete).

