# GET PRODUCT CATEGORY

> url: /category/{category_slug}

Response
```javascript
{
    "code": 200,
    "message": "OK",
    "data": {
        "id": 2,
        "name": "Komoditas Pangan",
        "slug": "komoditas-pangan",
        "img": "1b.jpg",
        "status_id": 1,
        "feature_status": 1,
        "sub_category": [
            {
                "id": 5,
                "name": "Minyak",
                "slug": "minyak",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 9,
                "name": "Gula",
                "slug": "gula",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 10,
                "name": "Beras",
                "slug": "beras",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 18,
                "name": "Terigu",
                "slug": "terigu",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 21,
                "name": "Teh",
                "slug": "teh",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 25,
                "name": "Udang",
                "slug": "udang",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 26,
                "name": "Cumi Cumi",
                "slug": "cumi-cumi",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 28,
                "name": "Daging & Ayam",
                "slug": "daging-ayam",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 29,
                "name": "sosis",
                "slug": "sosis",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 30,
                "name": "garam",
                "slug": "garam",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            },
            {
                "id": 34,
                "name": "Mentega&Margarine",
                "slug": "mentegamargarine",
                "img": null,
                "img_b2b": null,
                "status_id": 1,
                "fk_category": 2
            }
        ]
    }
}
```