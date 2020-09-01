# POST LOGIN USER

> url: /auth/login

Body Request
```javascript
{
    "email": "boni@worktrees.com",
    "password":"password"
}
```

Response
```javascript
{
    "code": 200,
    "message": "Login Success",
    "token_type": "bearer",
    "access_token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC9sb2NhbGhvc3Q6OTAwMFwvYXBpXC92MVwvYXV0aFwvbG9naW4iLCJpYXQiOjE1OTg5NDU3NDgsImV4cCI6MTYwMDE1NTM0OCwibmJmIjoxNTk4OTQ1NzQ4LCJqdGkiOiJZU1dOY1NWcW5TRnozZkRvIiwic3ViIjoxOCwicHJ2IjoiODdlMGFmMWVmOWZkMTU4MTJmZGVjOTcxNTNhMTRlMGIwNDc1NDZhYSJ9.FDt0VY7ierpwNzehOnQ83JmCejNt1EpTtkRmf5gf-HA",
    "expires_in": 20160,
    "profile": {
        "id": 18,
        "name": "Boni Worktrees",
        "email": "boni@worktrees.com",
        "roles_id": null,
        "users_status_id": 1,
        "email_verified_at": null,
        "level": [
            {
                "type_id": 2,
                "type_name": "B2C",
                "level_id": 4,
                "level_name": "Elite"
            },
            {
                "type_id": 1,
                "type_name": "B2B",
                "level_id": 7,
                "level_name": "Reguler"
            }
        ],
        "billing": [
            {
                "id": 4,
                "first_name": "Boni Worktrees",
                "last_name": null,
                "email": "hello@magnesia.agency",
                "country": "Indonesia",
                "province": "DKI Jakarta",
                "province_id": null,
                "city": "Kota Jakarta Pusat",
                "city_id": null,
                "district": "Kemayoran",
                "district_id": null,
                "address": "Jelambar",
                "postcode": "14450",
                "mobile_phone": "+6281211090020",
                "default": 0,
                "user_id": 18,
                "created_at": "2020-07-06 15:58:03",
                "updated_at": "2020-07-06 15:58:03"
            },
            {
                "id": 5,
                "first_name": "Boni Worktrees",
                "last_name": null,
                "email": "boni@worktrees.com",
                "country": "Indonesia",
                "province": "Banten",
                "province_id": null,
                "city": "Kota Tangerang",
                "city_id": null,
                "district": "Karawaci",
                "district_id": null,
                "address": "Jl Karawaci Raya no.56",
                "postcode": "12345",
                "mobile_phone": "0987654321",
                "default": 0,
                "user_id": 18,
                "created_at": "2020-07-13 15:14:15",
                "updated_at": "2020-07-13 15:14:15"
            }
        ],
        "shipping": [
            {
                "id": 10,
                "first_name": "Boni Worktrees",
                "last_name": null,
                "email": "boni@worktrees.com",
                "country": "Indonesia",
                "province": "DI Yogyakarta",
                "province_id": 5,
                "city": "Yogyakarta",
                "city_id": 501,
                "address": "Jl Gondomanan raya no.12",
                "postcode": "156789",
                "mobile_phone": "0987654321",
                "district": "Gondomanan",
                "district_id": 6984,
                "default": 0,
                "user_id": 18,
                "created_at": "2020-04-23 21:17:59",
                "updated_at": "2020-04-23 21:17:59"
            },
            {
                "id": 15,
                "first_name": "Boni Worktrees",
                "last_name": null,
                "email": "boni@worktrees.com",
                "country": "Indonesia",
                "province": "Banten",
                "province_id": 3,
                "city": "Tangerang Selatan",
                "city_id": 457,
                "address": "Jl. Sutera permai raya no.34",
                "postcode": "12345",
                "mobile_phone": "084587451245",
                "district": "Serpong Utara",
                "district_id": 6315,
                "default": 0,
                "user_id": 18,
                "created_at": "2020-06-11 17:00:45",
                "updated_at": "2020-06-11 17:00:45"
            },
            {
                "id": 30,
                "first_name": "Boni Worktrees",
                "last_name": null,
                "email": "boni@worktrees.com",
                "country": "Indonesia",
                "province": "DKI Jakarta",
                "province_id": 6,
                "city": "Kota Jakarta Selatan",
                "city_id": 153,
                "address": "Mampang raya 11",
                "postcode": "12345",
                "mobile_phone": "089876876756",
                "district": "Mampang Prapatan",
                "district_id": 2107,
                "default": 0,
                "user_id": 18,
                "created_at": "2020-06-30 11:05:25",
                "updated_at": "2020-06-30 11:05:25"
            },
            {
                "id": 38,
                "first_name": "Boni Worktrees",
                "last_name": null,
                "email": "boni@worktrees.com",
                "country": "Indonesia",
                "province": "Banten",
                "province_id": 3,
                "city": "Kota Tangerang",
                "city_id": 456,
                "address": "Jl Karawaci Raya no.56",
                "postcode": "12345",
                "mobile_phone": "0987654321",
                "district": "Karawaci",
                "district_id": 6304,
                "default": 0,
                "user_id": 18,
                "created_at": "2020-07-13 15:01:47",
                "updated_at": "2020-07-13 15:01:47"
            }
        ]
    }
}
```

Key| Description
------------ | -------------
access_token | Use for jwt auth with bearer
profile | to get the regis user information

