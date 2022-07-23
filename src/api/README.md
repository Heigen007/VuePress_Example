---
sidebar: auto
---

# API

## /getUsers?count=?

- Type: 'GET'
- Response: JSON

```json
{
  "users": [
    {
      "id": 1,
      "name": "John Doe",
      "email": "John@gmail.com"
    },
    ...
  ]
}
```

## /getUser?id=?

- Type: 'GET'
- Response: JSON

```json
{
  "user": {
    "id": 1,
    "name": "John Doe",
    "email": "John@gmail.com"
  }
}
```

## /createUser

- Type: 'POST'
- Request: JSON

```json
{
  "user": {
    "name": "Test User",
    "email": "testMail.mail.com"
  }
}
```

- Response: JSON

```json
{
  "result": "success"
}
// or
{
  "result": "error",
  "message": "SomeErrorMessage"
}
```
