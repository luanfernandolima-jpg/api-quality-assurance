# [POST /api/v1/courier] Login field accepts a single character

## Description

According to the business requirements, the **login** field must accept between **2 and 10 characters**. However, the API allows a courier to be created with a login containing only **1 character**.

## Steps to Reproduce

1. Send a **POST** request to the endpoint `/api/v1/courier`.
2. Use the following request body:

```json
{
  "login": "L",
  "password": "1234",
  "firstname": "Larissa"
}
```

3. Send the request.
4. Observe the API response.

## Expected Result

The API should reject the request when the **login** field contains fewer than **2 characters**, returning:

* **Status Code:** `400 Bad Request`

## Actual Result

The API accepts the request with a **1-character login**, returning:

* **Status Code:** `201 Created`

## Environment

* Postman
