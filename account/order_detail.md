# GET ORDER DETAIL FROM USER

> url: /auth/get_orders/b2c/{user_id}

Header Request

Key| Value
------------ | -------------
Authorization | Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC9sb2NhbGhvc3Q6OTAwMFwvYXBpXC92MVwvYXV0aFwvbG9naW4iLCJpYXQiOjE1OTg5NDU3NDgsImV4cCI6MTYwMDE1NTM0OCwibmJmIjoxNTk4OTQ1NzQ4LCJqdGkiOiJZU1dOY1NWcW5TRnozZkRvIiwic3ViIjoxOCwicHJ2IjoiODdlMGFmMWVmOWZkMTU4MTJmZGVjOTcxNTNhMTRlMGIwNDc1NDZhYSJ9.FDt0VY7ierpwNzehOnQ83JmCejNt1EpTtkRmf5gf-HA


Response
```javascript
{
    "code": 200,
    "message": "OK",
    "data": {
        "purchase_id": 212,
        "invoice_number": "INV200818052122",
        "paymentGatewayRefrence": null,
        "user_name": "Boni Worktrees",
        "user_email": "boni@worktrees.com",
        "user_phone_number": null,
        "purchase_date": "2020-08-18 00:00:00",
        "payment_method": null,
        "last_update_order": "2020-08-18 05:21:22",
        "shipping_country": "Indonesia",
        "shipping_address": "Jl. Sutera permai raya no.34",
        "shipping_address_note": null,
        "shipping_province": "Banten",
        "shipping_city": "Tangerang Selatan",
        "shipping_kecamatan": "Serpong Utara",
        "shipping_method": null,
        "shipping_zipcode": "12345",
        "order_note": null,
        "promo_code": null,
        "promo_number": null,
        "tax_price": null,
        "subtotal_price": 25000,
        "real_subtotal": 25000,
        "discount_type": null,
        "discount": null,
        "shipping_kurir": null,
        "invoice_template": null,
        "shipping_service_type": null,
        "shipping_estimate_date": null,
        "shipping_code": null,
        "shipping_price": 36000,
        "real_shipping_price": 36000,
        "purchase_total_price": 61000,
        "real_purchase_total_price": 61000,
        "currency": null,
        "currancy_rate": null,
        "purchase_location": null,
        "customer_identity": null,
        "customer_type_id": null,
        "pricing_type": null,
        "purchase_status_id": 5,
        "purchase_status": "Expired",
        "tb_purchasecol": null,
        "bill_email": "boni@worktrees.com",
        "bill_phone_number": "084587451245",
        "bill_country": "Indonesia",
        "bill_address": "Jl. Sutera permai raya no.34",
        "bill_address_note": null,
        "bill_province": "Banten",
        "bill_zipcode": "12345",
        "bill_city": "Tangerang Selatan",
        "bill_kecamatan": "Serpong Utara",
        "bill_name": "Boni Worktrees",
        "transaction_location": "nushinushi.id",
        "user_id": 18,
        "user": {
            "id": 18,
            "name": "Boni Worktrees",
            "phone": null,
            "email": "boni@worktrees.com",
            "email_verified_at": null,
            "created_at": "2020-05-01 16:11:00",
            "updated_at": "2020-08-30 23:35:39",
            "users_status_id": 1
        },
        "warehouse_order": [
            {
                "id": 225,
                "ref_warehouse_id": 29,
                "invoice": "INVO2008180521220",
                "warehouse_name": "NUSINDO CAB BOGOR",
                "shipping_method": "POS Indonesia (POS) - Express Next Day Barang - Etd 1 HARI Hari - Rp36,000",
                "shipping_charges": 36000,
                "shipping_waybill": null,
                "shipping_status": 8,
                "order_id": 212,
                "order_product": [
                    {
                        "tb_product_order_id": 335,
                        "o_variant_id": null,
                        "o_SKU_prod": null,
                        "o_SKU_per_item": null,
                        "o_prodname": "TROPICAL BOTOL 2 LITER",
                        "o_prod_variant": null,
                        "o_prod_option_group_name": null,
                        "option_value_name": null,
                        "o_prodprice": 25000,
                        "o_real_prodprice": 25000,
                        "o_prod_price_currency": "Rp",
                        "o_pricediscount": 0,
                        "o_price_method": null,
                        "o_qty": 1,
                        "o_total_price": 25000,
                        "o_real_total_price": 25000,
                        "o_prod_id": 81,
                        "o_merge_prod_id": 6362,
                        "o_point_product": null,
                        "o_satuan": null,
                        "warehouse_order_id": 225,
                        "order_id": 212,
                        "status_product_id": null,
                        "img_full_link": "imageproduct/Sfam3m3D5n3VFTaS3Sj6eWTTwEBv2cdhvbCCdguj.jpeg",
                        "warranty_name": null,
                        "warranty_description": null,
                        "warranty_claim_count": null,
                        "warranty_expired": null,
                        "created_at": "2020-08-18 17:21:22",
                        "updated_at": "2020-08-18 17:21:22",
                        "cancel_at": null
                    }
                ],
                "delivery_log": {
                    "1": {
                        "id": 72,
                        "desc": "Order is <span class=\"font-weight-bold\">Exception</span>",
                        "activity": "Exception",
                        "users_id": 18,
                        "order_warehouse_id": 225,
                        "order_id": null,
                        "created_at": "2020-09-01 15:27:03",
                        "updated_at": "2020-09-01 15:27:03"
                    },
                    "0": {
                        "id": 59,
                        "desc": "Order receive from <span class=\"font-weight-bold\">Boni Worktrees - NUSHINUSHI.ID</span>",
                        "activity": "Info Received",
                        "users_id": 18,
                        "order_warehouse_id": 225,
                        "order_id": null,
                        "created_at": "2020-08-18 17:21:22",
                        "updated_at": "2020-08-18 17:21:22"
                    }
                }
            }
        ]
    }
}
```