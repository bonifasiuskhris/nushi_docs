# POST SAVE SHIPPING ADDRESS

> url: /auth/store_ship

Header Request

Key| Value
------------ | -------------
Authorization | Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC9sb2NhbGhvc3Q6OTAwMFwvYXBpXC92MVwvYXV0aFwvbG9naW4iLCJpYXQiOjE1OTg5NDU3NDgsImV4cCI6MTYwMDE1NTM0OCwibmJmIjoxNTk4OTQ1NzQ4LCJqdGkiOiJZU1dOY1NWcW5TRnozZkRvIiwic3ViIjoxOCwicHJ2IjoiODdlMGFmMWVmOWZkMTU4MTJmZGVjOTcxNTNhMTRlMGIwNDc1NDZhYSJ9.FDt0VY7ierpwNzehOnQ83JmCejNt1EpTtkRmf5gf-HA

Body Request
```javascript
{
    "first_name": "Boni Worktrees",
    "email": "boni@worktrees.com",
    "mobile_phone": "0987654321",
    "country": "Indonesia",
    "province_id": "3", //id from rajaongkir api
    "province": "Banten", //name from rajaongkir api
    "city_id": "456", //city_id from rajaongkir api
    "city": "Kota Tangerang", //name from rajaongkir api
    "district_id": "6304", //district_id from rajaongkir api
    "district": "Karawaci", //name from rajaongkir api
    "address": "Jl Karawaci Raya no.56",
    "postcode": "12345",
    "id": "18" //user_id
}
```

Response
```javascript
{
    "code":200,
    "status": "success",
    "message": "Shipping address successfully created"
}
```