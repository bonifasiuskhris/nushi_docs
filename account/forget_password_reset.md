# POST FORGET PASSWORD EMAIL USER

> url: /password/reset

Body Request
```javascript
{
    "email":"boni@worktrees.com",
    "token":"249e1492e7f4f3371792a0e4fa03d1b8b10af7d2a7d9cd3f63e141d1fbca45a1",
    "password":"password",
    "password_confirmation":"password"
}
```

Response
```javascript
{
    "code":200,
    "status": "Your password has been reset!",
    "message": "Reset password success"
}
```