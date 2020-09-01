# GET PRODUCT DETAIL

> url: /product/b2c/{product_slug}?warehouse={warehouse_slug}

Response
```javascript
{
    "code": 200,
    "message": "OK",
    "data": {
        "id": 6337,
        "category": "B2C",
        "product": {
            "id": 133,
            "name": "Tan Baron Peppermint Tea 25 x 2 Gram",
            "short_name": "Tan Baron Pappermint Tea",
            "slug": "tan-baron-peppermint-tea-25-x-2-gram",
            "sku": null,
            "normal_price": 79000,
            "discount_price": null,
            "msrp_price": null,
            "msrp_discount": null,
            "store_price": null,
            "store_price_discount": null,
            "qrcode": null,
            "stock": 0,
            "weight": 2,
            "unit_id": 1,
            "unit_name": "pcs",
            "image": [
                {
                    "id": 139,
                    "image_url": "imageproduct/UGSWbD18S8FpcCMpS6qtHojns0ZxYtVvMIVB0Bjy.png",
                    "image_name": "Tan Baron Pappermint Tea.png",
                    "position": 1,
                    "product_id": 133,
                    "created_at": "2020-07-06 10:05:16",
                    "updated_at": "2020-07-06 10:05:16"
                }
            ],
            "collection_id": 1,
            "collection_name": "Nushi",
            "collection_slug": "nushi",
            "category_id": 2,
            "category_name": "Komoditas Pangan",
            "category_slug": "komoditas-pangan",
            "sub_category": [
                {
                    "id": 296,
                    "name": "Teh",
                    "slug": "teh"
                }
            ],
            "status_id": 1,
            "status_name": "Active",
            "status_slug": null,
            "mark_as_new": "Active",
            "apply_discount": "Inactive",
            "soldout_status": "Inactive",
            "featured_status": "Inactive",
            "variant": [],
            "description": null,
            "short_description": null,
            "created_at": "2020-07-06T03:05:16.000000Z",
            "updated_at": "2020-07-06T03:07:47.000000Z",
            "section": [
                {
                    "id": 185,
                    "section_id": 1,
                    "section_name": "Produk Terbaru",
                    "product_id": 133,
                    "product_name": "Tan Baron Peppermint Tea 25 x 2 Gram",
                    "product_slug": "tan-baron-peppermint-tea-25-x-2-gram",
                    "status_id": 1,
                    "status": "Active"
                }
            ]
        },
        "warehouse": {
            "id": 5,
            "name": "NUSINDO PUSAT",
            "slug": "nusindo-pusat",
            "location_id": 1,
            "location_name": "DKI Jakarta",
            "location_slug": "dki-jakarta",
            "address": "Gedung RNI Lt. 2\r\nJalan Denpasar Raya Kav. DIII Kuningan, Jakarta Selatan 12950",
            "contact_number": "077652279110",
            "category_id": 2,
            "category_name": "B2C",
            "status_id": 2,
            "status_name": "On",
            "currency_id": 1,
            "currency_symbol": "Rp",
            "currency_name": "Rupiah",
            "currency_rate": 13500,
            "currency_status": 1
        }
    }
}
```