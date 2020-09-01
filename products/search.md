# POST PRODUCT SEARCH

> url: /search?location={location_slug}

Body Request
```javascript
{
    "slug":"minyak goreng"
}
```

Response
```javascript
{
    "code": 200,
    "message": "OK",
    "data": [
        {
            "id": 6277,
            "category": "B2C",
            "product": {
                "id": 82,
                "name": "TROPICAL MINYAK GORENG 500ML REFFIL",
                "short_name": "TROPICAL Minyak Goreng",
                "slug": "tropical-minyak-goreng-500ml-reffil",
                "sku": null,
                "normal_price": 6683,
                "discount_price": null,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": null,
                "stock": 0,
                "weight": 500,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 92,
                        "image_url": "imageproduct/QkvSjxUzYYmn1jp8A3FdJ4w8w3VCsVpbGkueDoeG.jpeg",
                        "image_name": "Tropical Refill 1 L(1).jpg",
                        "position": 1,
                        "product_id": 82,
                        "created_at": "2020-06-30 14:25:42",
                        "updated_at": "2020-06-30 14:25:42"
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
                        "id": 338,
                        "name": "Minyak",
                        "slug": "minyak"
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
                "created_at": "2020-06-30T07:25:42.000000Z",
                "updated_at": "2020-08-10T04:35:04.000000Z",
                "section": []
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
        },
        {
            "id": 6272,
            "category": "B2C",
            "product": {
                "id": 74,
                "name": "Tropical Minyak Goreng 500ML Pouch ( isi 24 )",
                "short_name": null,
                "slug": "tropical-minyak-goreng-500ml-pouch-isi-24",
                "sku": null,
                "normal_price": 157400,
                "discount_price": null,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": null,
                "stock": 0,
                "weight": 0,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 87,
                        "image_url": "imageproduct/VGgRsOaPfHVz0xHZ9I9gZDCzsHmmaOSJJCU9gGMu.jpeg",
                        "image_name": "Tropical Refill 1 L(1).jpg",
                        "position": 1,
                        "product_id": 74,
                        "created_at": "2020-06-30 11:18:41",
                        "updated_at": "2020-06-30 11:18:41"
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
                        "id": 227,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Active",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [
                    {
                        "variant_id": 38,
                        "product_id": 42,
                        "name": "TROPICAL MINYAK GORENG REFFIL 1 L",
                        "slug": "tropical-minyak-goreng-reffil-1-l"
                    }
                ],
                "description": null,
                "short_description": null,
                "created_at": "2020-06-30T04:18:41.000000Z",
                "updated_at": "2020-06-30T08:21:18.000000Z",
                "section": []
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
        },
        {
            "id": 6092,
            "category": "B2C",
            "product": {
                "id": 40,
                "name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                "short_name": null,
                "slug": "tropical-minyak-goreng-2-liter-pouch-isi-6",
                "sku": "SKTGP",
                "normal_price": 154000,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 0,
                "unit_id": 1,
                "unit_name": "pcs",
                "image": [
                    {
                        "id": 28,
                        "image_url": "imageproduct/jyUbHfclseNNdIUSJzneqTSDfYnwqq84Vkckat5A.jpeg",
                        "image_name": "Tropical Refill 2L Paket.jpg",
                        "position": 1,
                        "product_id": 40,
                        "created_at": "2020-03-18 15:05:27",
                        "updated_at": "2020-06-23 16:35:01"
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
                        "id": 201,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Active",
                "variant": [],
                "description": "<h2>heading 1</h2><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse fermentum turpis ac tellus accumsan, at convallis nulla interdum. Donec tincidunt dui vel aliquam maximus. Morbi egestas diam pretium, consectetur sem sed, hendrerit metus. Aliquam in ante eu ex volutpat dignissim et in nunc. Maecenas vitae sollicitudin massa, sed vulputate enim. Fusce suscipit massa leo, id viverra mi lobortis nec. Fusce ultrices dolor sed mauris venenatis pharetra. Nulla vel ante et lorem vestibulum gravida. Pellentesque vestibulum est eu posuere venenatis. Pellentesque in eros a felis vehicula semper. Maecenas ut mi mattis, eleifend eros sit amet, placerat felis..</p>",
                "short_description": null,
                "created_at": "2020-03-18T08:05:27.000000Z",
                "updated_at": "2020-06-30T03:43:31.000000Z",
                "section": [
                    {
                        "id": 64,
                        "section_id": 1,
                        "section_name": "Produk Terbaru",
                        "product_id": 40,
                        "product_name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                        "product_slug": "tropical-minyak-goreng-2-liter-pouch-isi-6",
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
        },
        {
            "id": 2852,
            "category": "B2C",
            "product": {
                "id": 40,
                "name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                "short_name": null,
                "slug": "tropical-minyak-goreng-2-liter-pouch-isi-6",
                "sku": "SKTGP",
                "normal_price": 139500,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 0,
                "unit_id": 1,
                "unit_name": "pcs",
                "image": [
                    {
                        "id": 28,
                        "image_url": "imageproduct/jyUbHfclseNNdIUSJzneqTSDfYnwqq84Vkckat5A.jpeg",
                        "image_name": "Tropical Refill 2L Paket.jpg",
                        "position": 1,
                        "product_id": 40,
                        "created_at": "2020-03-18 15:05:27",
                        "updated_at": "2020-06-23 16:35:01"
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
                        "id": 201,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Active",
                "variant": [],
                "description": "<h2>heading 1</h2><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse fermentum turpis ac tellus accumsan, at convallis nulla interdum. Donec tincidunt dui vel aliquam maximus. Morbi egestas diam pretium, consectetur sem sed, hendrerit metus. Aliquam in ante eu ex volutpat dignissim et in nunc. Maecenas vitae sollicitudin massa, sed vulputate enim. Fusce suscipit massa leo, id viverra mi lobortis nec. Fusce ultrices dolor sed mauris venenatis pharetra. Nulla vel ante et lorem vestibulum gravida. Pellentesque vestibulum est eu posuere venenatis. Pellentesque in eros a felis vehicula semper. Maecenas ut mi mattis, eleifend eros sit amet, placerat felis..</p>",
                "short_description": null,
                "created_at": "2020-03-18T08:05:27.000000Z",
                "updated_at": "2020-06-30T03:43:31.000000Z",
                "section": [
                    {
                        "id": 64,
                        "section_id": 1,
                        "section_name": "Produk Terbaru",
                        "product_id": 40,
                        "product_name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                        "product_slug": "tropical-minyak-goreng-2-liter-pouch-isi-6",
                        "status_id": 1,
                        "status": "Active"
                    }
                ]
            },
            "warehouse": {
                "id": 1,
                "name": "NUSINDO CAB JAKARTA 1",
                "slug": "nusindo-cab-jakarta-1",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "JL. Pulo Kambing Raya, No. 30, Kawasan Industri Pulogadung, Kav. II Blok L/11, Jakarta, 13920, RW.11, Jatinegara, Cakung, East Jakarta City, Jakarta 13930",
                "contact_number": "123456789",
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
        },
        {
            "id": 5282,
            "category": "B2C",
            "product": {
                "id": 40,
                "name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                "short_name": null,
                "slug": "tropical-minyak-goreng-2-liter-pouch-isi-6",
                "sku": "SKTGP",
                "normal_price": 90000,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 0,
                "unit_id": 1,
                "unit_name": "pcs",
                "image": [
                    {
                        "id": 28,
                        "image_url": "imageproduct/jyUbHfclseNNdIUSJzneqTSDfYnwqq84Vkckat5A.jpeg",
                        "image_name": "Tropical Refill 2L Paket.jpg",
                        "position": 1,
                        "product_id": 40,
                        "created_at": "2020-03-18 15:05:27",
                        "updated_at": "2020-06-23 16:35:01"
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
                        "id": 201,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Active",
                "variant": [],
                "description": "<h2>heading 1</h2><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse fermentum turpis ac tellus accumsan, at convallis nulla interdum. Donec tincidunt dui vel aliquam maximus. Morbi egestas diam pretium, consectetur sem sed, hendrerit metus. Aliquam in ante eu ex volutpat dignissim et in nunc. Maecenas vitae sollicitudin massa, sed vulputate enim. Fusce suscipit massa leo, id viverra mi lobortis nec. Fusce ultrices dolor sed mauris venenatis pharetra. Nulla vel ante et lorem vestibulum gravida. Pellentesque vestibulum est eu posuere venenatis. Pellentesque in eros a felis vehicula semper. Maecenas ut mi mattis, eleifend eros sit amet, placerat felis..</p>",
                "short_description": null,
                "created_at": "2020-03-18T08:05:27.000000Z",
                "updated_at": "2020-06-30T03:43:31.000000Z",
                "section": [
                    {
                        "id": 64,
                        "section_id": 1,
                        "section_name": "Produk Terbaru",
                        "product_id": 40,
                        "product_name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                        "product_slug": "tropical-minyak-goreng-2-liter-pouch-isi-6",
                        "status_id": 1,
                        "status": "Active"
                    }
                ]
            },
            "warehouse": {
                "id": 31,
                "name": "NUSINDO CAB JAKARTA 2",
                "slug": "nusindo-cab-jakarta-2",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "Jl. Raya Rw. Bambu, RT.6/RW.8, Ps. Minggu, Kec. Ps. Minggu, Kota Jakarta Selatan, Daerah Khusus Ibukota Jakarta 12520",
                "contact_number": "123456789",
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
        },
        {
            "id": 5930,
            "category": "B2C",
            "product": {
                "id": 40,
                "name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                "short_name": null,
                "slug": "tropical-minyak-goreng-2-liter-pouch-isi-6",
                "sku": "SKTGP",
                "normal_price": 151000,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 0,
                "unit_id": 1,
                "unit_name": "pcs",
                "image": [
                    {
                        "id": 28,
                        "image_url": "imageproduct/jyUbHfclseNNdIUSJzneqTSDfYnwqq84Vkckat5A.jpeg",
                        "image_name": "Tropical Refill 2L Paket.jpg",
                        "position": 1,
                        "product_id": 40,
                        "created_at": "2020-03-18 15:05:27",
                        "updated_at": "2020-06-23 16:35:01"
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
                        "id": 201,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Active",
                "variant": [],
                "description": "<h2>heading 1</h2><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse fermentum turpis ac tellus accumsan, at convallis nulla interdum. Donec tincidunt dui vel aliquam maximus. Morbi egestas diam pretium, consectetur sem sed, hendrerit metus. Aliquam in ante eu ex volutpat dignissim et in nunc. Maecenas vitae sollicitudin massa, sed vulputate enim. Fusce suscipit massa leo, id viverra mi lobortis nec. Fusce ultrices dolor sed mauris venenatis pharetra. Nulla vel ante et lorem vestibulum gravida. Pellentesque vestibulum est eu posuere venenatis. Pellentesque in eros a felis vehicula semper. Maecenas ut mi mattis, eleifend eros sit amet, placerat felis..</p>",
                "short_description": null,
                "created_at": "2020-03-18T08:05:27.000000Z",
                "updated_at": "2020-06-30T03:43:31.000000Z",
                "section": [
                    {
                        "id": 64,
                        "section_id": 1,
                        "section_name": "Produk Terbaru",
                        "product_id": 40,
                        "product_name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                        "product_slug": "tropical-minyak-goreng-2-liter-pouch-isi-6",
                        "status_id": 1,
                        "status": "Active"
                    }
                ]
            },
            "warehouse": {
                "id": 43,
                "name": "NUSINDO CAB KANTOR PUSAT",
                "slug": "nusindo-cab-kantor-pusat",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "jl no.43",
                "contact_number": "123456789",
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
        },
        {
            "id": 2854,
            "category": "B2C",
            "product": {
                "id": 42,
                "name": "TROPICAL MINYAK GORENG REFFIL 1 L",
                "short_name": null,
                "slug": "tropical-minyak-goreng-reffil-1-l",
                "sku": "sktpg",
                "normal_price": 13150,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 1,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 35,
                        "image_url": "imageproduct/C1p4d53xEtyBxav4lhPJ1RSHMCugDh3NcnhvlbnD.jpeg",
                        "image_name": "Tropical Refill 1 L.jpg",
                        "position": 1,
                        "product_id": 42,
                        "created_at": "2020-06-23 16:30:39",
                        "updated_at": "2020-06-23 16:30:39"
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
                        "id": 332,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [
                    {
                        "variant_id": 33,
                        "product_id": 40,
                        "name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                        "slug": "tropical-minyak-goreng-2-liter-pouch-isi-6"
                    },
                    {
                        "variant_id": 36,
                        "product_id": 41,
                        "name": "TROPICAL MINYAK GORENG REFFIL 2 L",
                        "slug": "tropical-minyak-goreng-reffil-2-l"
                    }
                ],
                "description": "<p>this is description</p>",
                "short_description": "<p>this is summary descriptionn</p>",
                "created_at": "2020-04-02T08:23:01.000000Z",
                "updated_at": "2020-08-05T03:23:04.000000Z",
                "section": [
                    {
                        "id": 63,
                        "section_id": 1,
                        "section_name": "Produk Terbaru",
                        "product_id": 42,
                        "product_name": "TROPICAL MINYAK GORENG REFFIL 1 L",
                        "product_slug": "tropical-minyak-goreng-reffil-1-l",
                        "status_id": 1,
                        "status": "Active"
                    }
                ]
            },
            "warehouse": {
                "id": 1,
                "name": "NUSINDO CAB JAKARTA 1",
                "slug": "nusindo-cab-jakarta-1",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "JL. Pulo Kambing Raya, No. 30, Kawasan Industri Pulogadung, Kav. II Blok L/11, Jakarta, 13920, RW.11, Jatinegara, Cakung, East Jakarta City, Jakarta 13930",
                "contact_number": "123456789",
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
        },
        {
            "id": 6094,
            "category": "B2C",
            "product": {
                "id": 42,
                "name": "TROPICAL MINYAK GORENG REFFIL 1 L",
                "short_name": null,
                "slug": "tropical-minyak-goreng-reffil-1-l",
                "sku": "sktpg",
                "normal_price": 13383,
                "discount_price": null,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 1,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 35,
                        "image_url": "imageproduct/C1p4d53xEtyBxav4lhPJ1RSHMCugDh3NcnhvlbnD.jpeg",
                        "image_name": "Tropical Refill 1 L.jpg",
                        "position": 1,
                        "product_id": 42,
                        "created_at": "2020-06-23 16:30:39",
                        "updated_at": "2020-06-23 16:30:39"
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
                        "id": 332,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [
                    {
                        "variant_id": 33,
                        "product_id": 40,
                        "name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                        "slug": "tropical-minyak-goreng-2-liter-pouch-isi-6"
                    },
                    {
                        "variant_id": 36,
                        "product_id": 41,
                        "name": "TROPICAL MINYAK GORENG REFFIL 2 L",
                        "slug": "tropical-minyak-goreng-reffil-2-l"
                    }
                ],
                "description": "<p>this is description</p>",
                "short_description": "<p>this is summary descriptionn</p>",
                "created_at": "2020-04-02T08:23:01.000000Z",
                "updated_at": "2020-08-05T03:23:04.000000Z",
                "section": [
                    {
                        "id": 63,
                        "section_id": 1,
                        "section_name": "Produk Terbaru",
                        "product_id": 42,
                        "product_name": "TROPICAL MINYAK GORENG REFFIL 1 L",
                        "product_slug": "tropical-minyak-goreng-reffil-1-l",
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
        },
        {
            "id": 5284,
            "category": "B2C",
            "product": {
                "id": 42,
                "name": "TROPICAL MINYAK GORENG REFFIL 1 L",
                "short_name": null,
                "slug": "tropical-minyak-goreng-reffil-1-l",
                "sku": "sktpg",
                "normal_price": 13150,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 1,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 35,
                        "image_url": "imageproduct/C1p4d53xEtyBxav4lhPJ1RSHMCugDh3NcnhvlbnD.jpeg",
                        "image_name": "Tropical Refill 1 L.jpg",
                        "position": 1,
                        "product_id": 42,
                        "created_at": "2020-06-23 16:30:39",
                        "updated_at": "2020-06-23 16:30:39"
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
                        "id": 332,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [
                    {
                        "variant_id": 33,
                        "product_id": 40,
                        "name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                        "slug": "tropical-minyak-goreng-2-liter-pouch-isi-6"
                    },
                    {
                        "variant_id": 36,
                        "product_id": 41,
                        "name": "TROPICAL MINYAK GORENG REFFIL 2 L",
                        "slug": "tropical-minyak-goreng-reffil-2-l"
                    }
                ],
                "description": "<p>this is description</p>",
                "short_description": "<p>this is summary descriptionn</p>",
                "created_at": "2020-04-02T08:23:01.000000Z",
                "updated_at": "2020-08-05T03:23:04.000000Z",
                "section": [
                    {
                        "id": 63,
                        "section_id": 1,
                        "section_name": "Produk Terbaru",
                        "product_id": 42,
                        "product_name": "TROPICAL MINYAK GORENG REFFIL 1 L",
                        "product_slug": "tropical-minyak-goreng-reffil-1-l",
                        "status_id": 1,
                        "status": "Active"
                    }
                ]
            },
            "warehouse": {
                "id": 31,
                "name": "NUSINDO CAB JAKARTA 2",
                "slug": "nusindo-cab-jakarta-2",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "Jl. Raya Rw. Bambu, RT.6/RW.8, Ps. Minggu, Kec. Ps. Minggu, Kota Jakarta Selatan, Daerah Khusus Ibukota Jakarta 12520",
                "contact_number": "123456789",
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
        },
        {
            "id": 5932,
            "category": "B2C",
            "product": {
                "id": 42,
                "name": "TROPICAL MINYAK GORENG REFFIL 1 L",
                "short_name": null,
                "slug": "tropical-minyak-goreng-reffil-1-l",
                "sku": "sktpg",
                "normal_price": 55000,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 1,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 35,
                        "image_url": "imageproduct/C1p4d53xEtyBxav4lhPJ1RSHMCugDh3NcnhvlbnD.jpeg",
                        "image_name": "Tropical Refill 1 L.jpg",
                        "position": 1,
                        "product_id": 42,
                        "created_at": "2020-06-23 16:30:39",
                        "updated_at": "2020-06-23 16:30:39"
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
                        "id": 332,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [
                    {
                        "variant_id": 33,
                        "product_id": 40,
                        "name": "Tropical Minyak goreng 2 liter pouch ( isi 6 )",
                        "slug": "tropical-minyak-goreng-2-liter-pouch-isi-6"
                    },
                    {
                        "variant_id": 36,
                        "product_id": 41,
                        "name": "TROPICAL MINYAK GORENG REFFIL 2 L",
                        "slug": "tropical-minyak-goreng-reffil-2-l"
                    }
                ],
                "description": "<p>this is description</p>",
                "short_description": "<p>this is summary descriptionn</p>",
                "created_at": "2020-04-02T08:23:01.000000Z",
                "updated_at": "2020-08-05T03:23:04.000000Z",
                "section": [
                    {
                        "id": 63,
                        "section_id": 1,
                        "section_name": "Produk Terbaru",
                        "product_id": 42,
                        "product_name": "TROPICAL MINYAK GORENG REFFIL 1 L",
                        "product_slug": "tropical-minyak-goreng-reffil-1-l",
                        "status_id": 1,
                        "status": "Active"
                    }
                ]
            },
            "warehouse": {
                "id": 43,
                "name": "NUSINDO CAB KANTOR PUSAT",
                "slug": "nusindo-cab-kantor-pusat",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "jl no.43",
                "contact_number": "123456789",
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
        },
        {
            "id": 2847,
            "category": "B2C",
            "product": {
                "id": 39,
                "name": "Tropical Minyak goreng 1 liter pouch ( isi 12 )",
                "short_name": null,
                "slug": "tropical-minyak-goreng-1-liter-pouch-isi-12",
                "sku": "skip8ptcs",
                "normal_price": 159000,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 0,
                "unit_id": 1,
                "unit_name": "pcs",
                "image": [
                    {
                        "id": 15,
                        "image_url": "imageproduct/fBO5sKFc0hZGBpArYCZSod9OhzLdF9WPTooQXeWN.jpeg",
                        "image_name": "Tropical Karton 1 _ 2 L.jpg",
                        "position": 1,
                        "product_id": 39,
                        "created_at": "2020-03-18 11:55:55",
                        "updated_at": "2020-06-23 16:47:58"
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
                        "id": 198,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Active",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Active",
                "variant": [
                    {
                        "variant_id": 14,
                        "product_id": 37,
                        "name": "Tropical paket Minyak Goreng 2 liter Pouch  dan Gula Pasir Raja Gula 1 kg",
                        "slug": "tropical-paket-minyak-goreng-2-liter-pouch-dan-gula-pasir-raja-gula-1-kg"
                    },
                    {
                        "variant_id": 15,
                        "product_id": 38,
                        "name": "Tropical Paket minyak goreng isi 3 Pouch ( 1 Litter)",
                        "slug": "tropical-paket-minyak-goreng-isi-3-pouch-1-litter"
                    }
                ],
                "description": "<ul><li>1.Soft touch, easy-to-grip, light weight and slim.</li><li>2.Allow full access to controls and ports,camera lens cutout.</li><li>3.Impact protection and scratch resistance.</li><li>4.Fully protects around the edges of your cellphone, avoid laying or falling directly on its screen. Snap on, easy to install and remove.ee</li></ul>",
                "short_description": null,
                "created_at": "2020-03-12T04:46:10.000000Z",
                "updated_at": "2020-06-30T03:36:40.000000Z",
                "section": []
            },
            "warehouse": {
                "id": 1,
                "name": "NUSINDO CAB JAKARTA 1",
                "slug": "nusindo-cab-jakarta-1",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "JL. Pulo Kambing Raya, No. 30, Kawasan Industri Pulogadung, Kav. II Blok L/11, Jakarta, 13920, RW.11, Jatinegara, Cakung, East Jakarta City, Jakarta 13930",
                "contact_number": "123456789",
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
        },
        {
            "id": 6087,
            "category": "B2C",
            "product": {
                "id": 39,
                "name": "Tropical Minyak goreng 1 liter pouch ( isi 12 )",
                "short_name": null,
                "slug": "tropical-minyak-goreng-1-liter-pouch-isi-12",
                "sku": "skip8ptcs",
                "normal_price": 157800,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 0,
                "unit_id": 1,
                "unit_name": "pcs",
                "image": [
                    {
                        "id": 15,
                        "image_url": "imageproduct/fBO5sKFc0hZGBpArYCZSod9OhzLdF9WPTooQXeWN.jpeg",
                        "image_name": "Tropical Karton 1 _ 2 L.jpg",
                        "position": 1,
                        "product_id": 39,
                        "created_at": "2020-03-18 11:55:55",
                        "updated_at": "2020-06-23 16:47:58"
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
                        "id": 198,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Active",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Active",
                "variant": [
                    {
                        "variant_id": 14,
                        "product_id": 37,
                        "name": "Tropical paket Minyak Goreng 2 liter Pouch  dan Gula Pasir Raja Gula 1 kg",
                        "slug": "tropical-paket-minyak-goreng-2-liter-pouch-dan-gula-pasir-raja-gula-1-kg"
                    },
                    {
                        "variant_id": 15,
                        "product_id": 38,
                        "name": "Tropical Paket minyak goreng isi 3 Pouch ( 1 Litter)",
                        "slug": "tropical-paket-minyak-goreng-isi-3-pouch-1-litter"
                    }
                ],
                "description": "<ul><li>1.Soft touch, easy-to-grip, light weight and slim.</li><li>2.Allow full access to controls and ports,camera lens cutout.</li><li>3.Impact protection and scratch resistance.</li><li>4.Fully protects around the edges of your cellphone, avoid laying or falling directly on its screen. Snap on, easy to install and remove.ee</li></ul>",
                "short_description": null,
                "created_at": "2020-03-12T04:46:10.000000Z",
                "updated_at": "2020-06-30T03:36:40.000000Z",
                "section": []
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
        },
        {
            "id": 5277,
            "category": "B2C",
            "product": {
                "id": 39,
                "name": "Tropical Minyak goreng 1 liter pouch ( isi 12 )",
                "short_name": null,
                "slug": "tropical-minyak-goreng-1-liter-pouch-isi-12",
                "sku": "skip8ptcs",
                "normal_price": 50000,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 0,
                "unit_id": 1,
                "unit_name": "pcs",
                "image": [
                    {
                        "id": 15,
                        "image_url": "imageproduct/fBO5sKFc0hZGBpArYCZSod9OhzLdF9WPTooQXeWN.jpeg",
                        "image_name": "Tropical Karton 1 _ 2 L.jpg",
                        "position": 1,
                        "product_id": 39,
                        "created_at": "2020-03-18 11:55:55",
                        "updated_at": "2020-06-23 16:47:58"
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
                        "id": 198,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Active",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Active",
                "variant": [
                    {
                        "variant_id": 14,
                        "product_id": 37,
                        "name": "Tropical paket Minyak Goreng 2 liter Pouch  dan Gula Pasir Raja Gula 1 kg",
                        "slug": "tropical-paket-minyak-goreng-2-liter-pouch-dan-gula-pasir-raja-gula-1-kg"
                    },
                    {
                        "variant_id": 15,
                        "product_id": 38,
                        "name": "Tropical Paket minyak goreng isi 3 Pouch ( 1 Litter)",
                        "slug": "tropical-paket-minyak-goreng-isi-3-pouch-1-litter"
                    }
                ],
                "description": "<ul><li>1.Soft touch, easy-to-grip, light weight and slim.</li><li>2.Allow full access to controls and ports,camera lens cutout.</li><li>3.Impact protection and scratch resistance.</li><li>4.Fully protects around the edges of your cellphone, avoid laying or falling directly on its screen. Snap on, easy to install and remove.ee</li></ul>",
                "short_description": null,
                "created_at": "2020-03-12T04:46:10.000000Z",
                "updated_at": "2020-06-30T03:36:40.000000Z",
                "section": []
            },
            "warehouse": {
                "id": 31,
                "name": "NUSINDO CAB JAKARTA 2",
                "slug": "nusindo-cab-jakarta-2",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "Jl. Raya Rw. Bambu, RT.6/RW.8, Ps. Minggu, Kec. Ps. Minggu, Kota Jakarta Selatan, Daerah Khusus Ibukota Jakarta 12520",
                "contact_number": "123456789",
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
        },
        {
            "id": 5925,
            "category": "B2C",
            "product": {
                "id": 39,
                "name": "Tropical Minyak goreng 1 liter pouch ( isi 12 )",
                "short_name": null,
                "slug": "tropical-minyak-goreng-1-liter-pouch-isi-12",
                "sku": "skip8ptcs",
                "normal_price": 50000,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 0,
                "unit_id": 1,
                "unit_name": "pcs",
                "image": [
                    {
                        "id": 15,
                        "image_url": "imageproduct/fBO5sKFc0hZGBpArYCZSod9OhzLdF9WPTooQXeWN.jpeg",
                        "image_name": "Tropical Karton 1 _ 2 L.jpg",
                        "position": 1,
                        "product_id": 39,
                        "created_at": "2020-03-18 11:55:55",
                        "updated_at": "2020-06-23 16:47:58"
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
                        "id": 198,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Active",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Active",
                "variant": [
                    {
                        "variant_id": 14,
                        "product_id": 37,
                        "name": "Tropical paket Minyak Goreng 2 liter Pouch  dan Gula Pasir Raja Gula 1 kg",
                        "slug": "tropical-paket-minyak-goreng-2-liter-pouch-dan-gula-pasir-raja-gula-1-kg"
                    },
                    {
                        "variant_id": 15,
                        "product_id": 38,
                        "name": "Tropical Paket minyak goreng isi 3 Pouch ( 1 Litter)",
                        "slug": "tropical-paket-minyak-goreng-isi-3-pouch-1-litter"
                    }
                ],
                "description": "<ul><li>1.Soft touch, easy-to-grip, light weight and slim.</li><li>2.Allow full access to controls and ports,camera lens cutout.</li><li>3.Impact protection and scratch resistance.</li><li>4.Fully protects around the edges of your cellphone, avoid laying or falling directly on its screen. Snap on, easy to install and remove.ee</li></ul>",
                "short_description": null,
                "created_at": "2020-03-12T04:46:10.000000Z",
                "updated_at": "2020-06-30T03:36:40.000000Z",
                "section": []
            },
            "warehouse": {
                "id": 43,
                "name": "NUSINDO CAB KANTOR PUSAT",
                "slug": "nusindo-cab-kantor-pusat",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "jl no.43",
                "contact_number": "123456789",
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
        },
        {
            "id": 2853,
            "category": "B2C",
            "product": {
                "id": 41,
                "name": "TROPICAL MINYAK GORENG REFFIL 2 L",
                "short_name": null,
                "slug": "tropical-minyak-goreng-reffil-2-l",
                "sku": "skmhy99",
                "normal_price": 25667,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 2,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 36,
                        "image_url": "imageproduct/Q1ezWsHh69MJL3YzkDyITXvBQtwMyIzLnUk5NsBy.jpeg",
                        "image_name": "Tropical Refill 2 L.jpg",
                        "position": 1,
                        "product_id": 41,
                        "created_at": "2020-06-23 16:32:01",
                        "updated_at": "2020-06-23 16:32:01"
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
                        "id": 333,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [],
                "description": "<p>bisa kan???</p>",
                "short_description": null,
                "created_at": "2020-03-19T09:49:36.000000Z",
                "updated_at": "2020-08-05T03:26:23.000000Z",
                "section": []
            },
            "warehouse": {
                "id": 1,
                "name": "NUSINDO CAB JAKARTA 1",
                "slug": "nusindo-cab-jakarta-1",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "JL. Pulo Kambing Raya, No. 30, Kawasan Industri Pulogadung, Kav. II Blok L/11, Jakarta, 13920, RW.11, Jatinegara, Cakung, East Jakarta City, Jakarta 13930",
                "contact_number": "123456789",
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
        },
        {
            "id": 6093,
            "category": "B2C",
            "product": {
                "id": 41,
                "name": "TROPICAL MINYAK GORENG REFFIL 2 L",
                "short_name": null,
                "slug": "tropical-minyak-goreng-reffil-2-l",
                "sku": "skmhy99",
                "normal_price": 26167,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 2,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 36,
                        "image_url": "imageproduct/Q1ezWsHh69MJL3YzkDyITXvBQtwMyIzLnUk5NsBy.jpeg",
                        "image_name": "Tropical Refill 2 L.jpg",
                        "position": 1,
                        "product_id": 41,
                        "created_at": "2020-06-23 16:32:01",
                        "updated_at": "2020-06-23 16:32:01"
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
                        "id": 333,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [],
                "description": "<p>bisa kan???</p>",
                "short_description": null,
                "created_at": "2020-03-19T09:49:36.000000Z",
                "updated_at": "2020-08-05T03:26:23.000000Z",
                "section": []
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
        },
        {
            "id": 5283,
            "category": "B2C",
            "product": {
                "id": 41,
                "name": "TROPICAL MINYAK GORENG REFFIL 2 L",
                "short_name": null,
                "slug": "tropical-minyak-goreng-reffil-2-l",
                "sku": "skmhy99",
                "normal_price": 25667,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 2,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 36,
                        "image_url": "imageproduct/Q1ezWsHh69MJL3YzkDyITXvBQtwMyIzLnUk5NsBy.jpeg",
                        "image_name": "Tropical Refill 2 L.jpg",
                        "position": 1,
                        "product_id": 41,
                        "created_at": "2020-06-23 16:32:01",
                        "updated_at": "2020-06-23 16:32:01"
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
                        "id": 333,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [],
                "description": "<p>bisa kan???</p>",
                "short_description": null,
                "created_at": "2020-03-19T09:49:36.000000Z",
                "updated_at": "2020-08-05T03:26:23.000000Z",
                "section": []
            },
            "warehouse": {
                "id": 31,
                "name": "NUSINDO CAB JAKARTA 2",
                "slug": "nusindo-cab-jakarta-2",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "Jl. Raya Rw. Bambu, RT.6/RW.8, Ps. Minggu, Kec. Ps. Minggu, Kota Jakarta Selatan, Daerah Khusus Ibukota Jakarta 12520",
                "contact_number": "123456789",
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
        },
        {
            "id": 5931,
            "category": "B2C",
            "product": {
                "id": 41,
                "name": "TROPICAL MINYAK GORENG REFFIL 2 L",
                "short_name": null,
                "slug": "tropical-minyak-goreng-reffil-2-l",
                "sku": "skmhy99",
                "normal_price": 30000,
                "discount_price": 0,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 2,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 36,
                        "image_url": "imageproduct/Q1ezWsHh69MJL3YzkDyITXvBQtwMyIzLnUk5NsBy.jpeg",
                        "image_name": "Tropical Refill 2 L.jpg",
                        "position": 1,
                        "product_id": 41,
                        "created_at": "2020-06-23 16:32:01",
                        "updated_at": "2020-06-23 16:32:01"
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
                        "id": 333,
                        "name": "Minyak",
                        "slug": "minyak"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Inactive",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [],
                "description": "<p>bisa kan???</p>",
                "short_description": null,
                "created_at": "2020-03-19T09:49:36.000000Z",
                "updated_at": "2020-08-05T03:26:23.000000Z",
                "section": []
            },
            "warehouse": {
                "id": 43,
                "name": "NUSINDO CAB KANTOR PUSAT",
                "slug": "nusindo-cab-kantor-pusat",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "jl no.43",
                "contact_number": "123456789",
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
        },
        {
            "id": 2855,
            "category": "B2C",
            "product": {
                "id": 37,
                "name": "Tropical paket Minyak Goreng 2 liter Pouch  dan Gula Pasir Raja Gula 1 kg",
                "short_name": null,
                "slug": "tropical-paket-minyak-goreng-2-liter-pouch-dan-gula-pasir-raja-gula-1-kg",
                "sku": "skip8bns",
                "normal_price": 70000,
                "discount_price": 65000,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 2,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 13,
                        "image_url": "imageproduct/334cI1Kpg6JwPEMJI2ThuLYB256kMJbkZSN08Udn.jpeg",
                        "image_name": "Tropical Refill 2 L.jpg",
                        "position": 1,
                        "product_id": 37,
                        "created_at": "2020-03-18 11:42:59",
                        "updated_at": "2020-06-23 16:50:15"
                    },
                    {
                        "id": 37,
                        "image_url": "imageproduct/LLLEwJNsCHvd2NDsVZf6aR3nrfSzutoMgBjA2DB7.jpeg",
                        "image_name": "Raja Gula 1Kg.jpg",
                        "position": 1,
                        "product_id": 37,
                        "created_at": "2020-06-23 16:50:38",
                        "updated_at": "2020-06-30 10:38:32"
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
                        "id": 218,
                        "name": "Minyak",
                        "slug": "minyak"
                    },
                    {
                        "id": 219,
                        "name": "Gula",
                        "slug": "gula"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Active",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [
                    {
                        "variant_id": 30,
                        "product_id": 39,
                        "name": "Tropical Minyak goreng 1 liter pouch ( isi 12 )",
                        "slug": "tropical-minyak-goreng-1-liter-pouch-isi-12"
                    },
                    {
                        "variant_id": 32,
                        "product_id": 36,
                        "name": "RAJA GULA 5kg",
                        "slug": "raja-gula-5kg"
                    }
                ],
                "description": "<ul><li>1.Soft touch, easy-to-grip, light weight and slim.</li><li>2.Allow full access to controls and ports,camera lens cutout.</li><li>3.Impact protection and scratch resistance.</li><li>4.Fully protects around the edges of your cellphone, avoid laying or falling directly on its screen. Snap on, easy to install and remove.</li></ul>",
                "short_description": null,
                "created_at": "2020-03-12T04:14:24.000000Z",
                "updated_at": "2020-06-30T07:03:34.000000Z",
                "section": []
            },
            "warehouse": {
                "id": 1,
                "name": "NUSINDO CAB JAKARTA 1",
                "slug": "nusindo-cab-jakarta-1",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "JL. Pulo Kambing Raya, No. 30, Kawasan Industri Pulogadung, Kav. II Blok L/11, Jakarta, 13920, RW.11, Jatinegara, Cakung, East Jakarta City, Jakarta 13930",
                "contact_number": "123456789",
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
        },
        {
            "id": 5285,
            "category": "B2C",
            "product": {
                "id": 37,
                "name": "Tropical paket Minyak Goreng 2 liter Pouch  dan Gula Pasir Raja Gula 1 kg",
                "short_name": null,
                "slug": "tropical-paket-minyak-goreng-2-liter-pouch-dan-gula-pasir-raja-gula-1-kg",
                "sku": "skip8bns",
                "normal_price": 70000,
                "discount_price": 65000,
                "msrp_price": null,
                "msrp_discount": null,
                "store_price": null,
                "store_price_discount": null,
                "qrcode": "",
                "stock": 0,
                "weight": 2,
                "unit_id": 3,
                "unit_name": "liter",
                "image": [
                    {
                        "id": 13,
                        "image_url": "imageproduct/334cI1Kpg6JwPEMJI2ThuLYB256kMJbkZSN08Udn.jpeg",
                        "image_name": "Tropical Refill 2 L.jpg",
                        "position": 1,
                        "product_id": 37,
                        "created_at": "2020-03-18 11:42:59",
                        "updated_at": "2020-06-23 16:50:15"
                    },
                    {
                        "id": 37,
                        "image_url": "imageproduct/LLLEwJNsCHvd2NDsVZf6aR3nrfSzutoMgBjA2DB7.jpeg",
                        "image_name": "Raja Gula 1Kg.jpg",
                        "position": 1,
                        "product_id": 37,
                        "created_at": "2020-06-23 16:50:38",
                        "updated_at": "2020-06-30 10:38:32"
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
                        "id": 218,
                        "name": "Minyak",
                        "slug": "minyak"
                    },
                    {
                        "id": 219,
                        "name": "Gula",
                        "slug": "gula"
                    }
                ],
                "status_id": 1,
                "status_name": "Active",
                "status_slug": null,
                "mark_as_new": "Active",
                "apply_discount": "Inactive",
                "soldout_status": "Inactive",
                "featured_status": "Inactive",
                "variant": [
                    {
                        "variant_id": 30,
                        "product_id": 39,
                        "name": "Tropical Minyak goreng 1 liter pouch ( isi 12 )",
                        "slug": "tropical-minyak-goreng-1-liter-pouch-isi-12"
                    },
                    {
                        "variant_id": 32,
                        "product_id": 36,
                        "name": "RAJA GULA 5kg",
                        "slug": "raja-gula-5kg"
                    }
                ],
                "description": "<ul><li>1.Soft touch, easy-to-grip, light weight and slim.</li><li>2.Allow full access to controls and ports,camera lens cutout.</li><li>3.Impact protection and scratch resistance.</li><li>4.Fully protects around the edges of your cellphone, avoid laying or falling directly on its screen. Snap on, easy to install and remove.</li></ul>",
                "short_description": null,
                "created_at": "2020-03-12T04:14:24.000000Z",
                "updated_at": "2020-06-30T07:03:34.000000Z",
                "section": []
            },
            "warehouse": {
                "id": 31,
                "name": "NUSINDO CAB JAKARTA 2",
                "slug": "nusindo-cab-jakarta-2",
                "location_id": 1,
                "location_name": "DKI Jakarta",
                "location_slug": "dki-jakarta",
                "address": "Jl. Raya Rw. Bambu, RT.6/RW.8, Ps. Minggu, Kec. Ps. Minggu, Kota Jakarta Selatan, Daerah Khusus Ibukota Jakarta 12520",
                "contact_number": "123456789",
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
    ],
    "links": {
        "first": "http://localhost:9000/api/v1/search?page=1",
        "last": "http://localhost:9000/api/v1/search?page=2",
        "prev": null,
        "next": "http://localhost:9000/api/v1/search?page=2"
    },
    "meta": {
        "current_page": 1,
        "from": 1,
        "last_page": 2,
        "path": "http://localhost:9000/api/v1/search",
        "per_page": 20,
        "to": 20,
        "total": 23
    }
}
```