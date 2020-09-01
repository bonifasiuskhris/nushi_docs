# GET PROMO DETAIL

> url: /promo/{promo_code}

Response
```javascript
{
    "code": 200,
    "message": "OK",
    "data": {
        "id": 4,
        "name": null,
        "description": null,
        "img": null,
        "img_name": null,
        "promo_usage": null,
        "promo_remaining": 9,
        "promo_code": "jadskBaa",
        "promo_total": 9,
        "start_date": "2020-04-15",
        "end_date": "2020-04-15",
        "created_date": null,
        "discount_percent": 9,
        "discount_amount": null,
        "min_purchase": 75000,
        "max_purchase": 100000,
        "promo_target_user": 3,
        "promo_statusid": 1,
        "discount_type_id": 1,
        "promo_type": {
            "promo_target_1": 3,
            "promo_target": "Per user"
        },
        "status": {
            "promo_status_id": 1,
            "promo_status_name": "On"
        },
        "discount_type": {
            "id": 1,
            "discount_name": "percent"
        },
        "specific_user": [
            {
                "promo_spesific_id": 2,
                "promo_email": "dirszas14@gmail.com",
                "promo_code_tb_id": 4,
                "created_at": "2020-04-15 13:34:16",
                "updated_at": "2020-04-15 13:34:16"
            }
        ]
    }
}
```