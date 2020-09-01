# POST REGISTER USER

> url: /register

Body Request
```javascript
{
    "name":"Boni Test",
    "email": "aspal12@hotmail.com",
    "password":"password",
    "password_confirmation":"password"
}
```

Response
```javascript
{
    "access_token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC9sb2NhbGhvc3Q6OTAwMFwvYXBpXC92MVwvcmVnaXN0ZXIiLCJpYXQiOjE1OTQ1NjAzMTIsImV4cCI6MTU5NDczMzExMiwibmJmIjoxNTk0NTYwMzEyLCJqdGkiOiJ3UFpXRlFnTld4dGMxOEZrIiwic3ViIjo1MSwicHJ2IjoiODdlMGFmMWVmOWZkMTU4MTJmZGVjOTcxNTNhMTRlMGIwNDc1NDZhYSJ9.8yjAiIietquR-5mq8a2O7itx-5NtnquWAqe57A1TRvA",
    "token_type": "bearer",
    "expires_in": 2880,
    "message": "Login Success",
    "profile": {
        "id": 51,
        "name": "Boni Test",
        "email": "aspal12@hotmail.com",
        "roles_id": null,
        "users_status_id": 1,
        "level": [
            {
                "type_id": 2,
                "type_name": "B2C",
                "level_id": 8,
                "level_name": "Reguler"
            }
        ],
        "billing": [],
        "shipping": []
    }
}
```

Key| Description
------------ | -------------
access_token | Use for jwt auth with bearer
profile | to get the regis user information

