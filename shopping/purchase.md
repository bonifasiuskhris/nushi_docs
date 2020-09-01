# POST SAVE SHIPPING ADDRESS

> url: /auth/save_order

Header Request

Key| Value
------------ | -------------
Authorization | Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC9sb2NhbGhvc3Q6OTAwMFwvYXBpXC92MVwvYXV0aFwvbG9naW4iLCJpYXQiOjE1OTg5NDU3NDgsImV4cCI6MTYwMDE1NTM0OCwibmJmIjoxNTk4OTQ1NzQ4LCJqdGkiOiJZU1dOY1NWcW5TRnozZkRvIiwic3ViIjoxOCwicHJ2IjoiODdlMGFmMWVmOWZkMTU4MTJmZGVjOTcxNTNhMTRlMGIwNDc1NDZhYSJ9.FDt0VY7ierpwNzehOnQ83JmCejNt1EpTtkRmf5gf-HA

Body Request
```javascript
{
    "selected_shipping": "10", //selected shipping ID
    "promo_code": null,
    "shipping_method": [ //An array of shipping method for each selected product warehouse
        {
            "warehouse_name": "NUSINDO PUSAT",
            "method": "Jalur Nugraha Ekakurir (JNE) - REG - Etd 1-2 Hari - Rp18,000",
            "price": "18000",
            "kurir_paket": "jne"
            //all pricing is from rajaongkir api
        }
    ],
    "selected_billing": "10", //selected billing ID
    "selected_warehouse": "nusindo-pusat", //selected warehouse when customer purchase
    "warehouse_category": "B2C", //Default
    "userID": "18", //User ID
    "product_warehouses": [ //An array of warehouse if the customer buys from multiple warehouse
        "NUSINDO PUSAT"
    ],
    "product": [
        {
            "id": "nusindo-pusat_118", //cart ID
            "name": "Daging Sapi (potongan)", //product name
            "price": 92000, //product individual price
            "quantity": "1", //product quantity
            "product_id": 118, //product id
            "current_warehouse": "nusindo-pusat",//selected warehouse
            "product_warehouse_id": 6315, //product to warehouse id
            "product_warehouse": "NUSINDO PUSAT", //product warehouse
            "collection_name": "Nushi", //collection name
            "collection_slug": "nushi", //collection slug
            "category_name": "Komoditas Pangan", //category name
            "category_slug": "komoditas-pangan", //category slug
            "normal_price": 92000, //product individual normal price
            "discount_status": "Inactive", //discount status
            "discount_price": null, //product discount price if active
            "slug": "daging-sapi-potongan", //product slug
            "image": "imageproduct/uOyoHK0umZUbuqusq9yRJd2CELhi6T9TIoftjmNb.jpeg", //product image
            "currency": "Rp" //product currency
        },
        {
            "id": "nusindo-pusat_112",
            "name": "Garam Cap Segitiga G",
            "price": 5000,
            "quantity": "1",
            "product_id": 112,
            "current_warehouse": "nusindo-pusat",
            "product_warehouse_id": 6306,
            "product_warehouse": "NUSINDO PUSAT",
            "collection_name": "Nushi",
            "collection_slug": "nushi",
            "category_name": "Komoditas Pangan",
            "category_slug": "komoditas-pangan",
            "normal_price": 5000,
            "discount_status": "Inactive",
            "discount_price": null,
            "slug": "garam-cap-segitiga-g",
            "image": "imageproduct/hdsLWnQzv5qlOkk8CGU2pGrXg4EPmcn6mtrCJknY.jpeg",
            "currency": "Rp"
        }
    ],
    "same": "1", //1(true) if shipping and billing address is the same, 0(false) if different
    "subtotal": "97000", //subtotal before shipping
    "total": "115000", //total price include shipping and promo
    "shipping_price": "18000" //total shipping price
}
```

Response
```javascript
{
    "code":200,
    "status": "success",
    "message": "Order Saved",
    "data": {
        "purchase_id": 153,
        "purchase_invoice": "INV200715030420"
    }
}
```