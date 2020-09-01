# POST CHANGE PASSWORD USER

> url: /auth/change_password

Header Request

Key| Value
------------ | -------------
Authorization | Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC9sb2NhbGhvc3Q6OTAwMFwvYXBpXC92MVwvYXV0aFwvbG9naW4iLCJpYXQiOjE1OTg5NDU3NDgsImV4cCI6MTYwMDE1NTM0OCwibmJmIjoxNTk4OTQ1NzQ4LCJqdGkiOiJZU1dOY1NWcW5TRnozZkRvIiwic3ViIjoxOCwicHJ2IjoiODdlMGFmMWVmOWZkMTU4MTJmZGVjOTcxNTNhMTRlMGIwNDc1NDZhYSJ9.FDt0VY7ierpwNzehOnQ83JmCejNt1EpTtkRmf5gf-HA

Body Request
```javascript
{
    "current_password":"password",
    "password":"newpassword",
    "password_confirmation":"newpassword"
}
```

Response
```javascript
{
    "code":200,
    "message": "Password changed successfully"
}
```