# Запроc получения данных о товаре

## Request URL
https://www.wildberries.ru/__internal/card/cards/v4/detail?appType=1&curr=rub&dest=-5854093&spp=30&hide_vflags=4294967296&hide_dflags=1048576&mdg=127&mtype=257&lang=ru&ab_testing=false&nm=1289478431
## Request Method
GET
## Path
/__internal/card/cards/v4/detail
## Response Status
200 ОК
## Content-Type
application/json
## Response
```JSON
{
	"products": [
		{
			"id": 1289478431,
			"root": 3041831355,
			"kindId": 2,
			"brand": "tivore",
			"brandId": 312283976,
			"siteBrandId": 0,
			"colors": [
				{
					"name": "черный",
					"id": 0
				}
			],
			"subjectId": 69,
			"subjectParentId": 1,
			"name": "Платье вечернее длинное",
			"entity": "",
			"matchId": 0,
			"supplier": "tivore",
			"supplierId": 381364,
			"supplierRating": 4.7,
			"supplierFlags": 12240,
			"pics": 7,
			"picsUpdate": 0,
			"rating": 4,
			"reviewRating": 4.4,
			"feedbacks": 173,
			"panelPromoId": 1056340,
			"volume": 99,
			"weight": 0.995,
			"viewFlags": 8590483586,
			"isNew": true,
			"promotions": [
				1003864,
				1003955,
				1005085,
				1006756,
				1007034,
				1007070,
				1011260,
				1015919,
				1020413,
				1022719,
				1023420,
				1023916,
				1025692,
				1028606,
				1029080,
				1038164,
				1040419,
				1047178,
				1049475,
				1049703,
				1050892,
				1053937,
				1055309,
				1055323,
				1055797,
				1055891,
				1056340,
				1056446,
				1056876,
				1056975
			],
			"sizes": [
				{
					"name": "46-48",
					"origName": "L",
					"rank": 646494,
					"optionId": 1903068409,
					"stocks": []
				},
				{
					"name": "44-46",
					"origName": "M",
					"rank": 596269,
					"optionId": 1903068410,
					"stocks": [
						{
							"wh": 6269589634,
							"dtype": 6614249635848,
							"ndtype": 197124,
							"dist": 4048,
							"qty": 1,
							"priority": 12442,
							"time1": 8,
							"time2": 100
						}
					],
					"time1": 8,
					"time2": 100,
					"wh": 6269589634,
					"dtype": 6614249635848,
					"ndtype": 197124,
					"dist": 4048,
					"price": {
						"basic": 1000000,
						"product": 332400,
						"logistics": 0,
						"return": 0,
						"cashback": 0,
						"wallet": 0
					},
					"saleConditions": 134217728,
					"payload": "AyrJFEVQL0tqtPZQY42Gbg1tOIO7KLJ/1PeUKyxDjkP0OB0gDCuBjdRcLt9S9p6JCeOBb3FllKC8Pk+1moXvn+qeedB9KyLOs0RstXspJPANrLn01PjkUVynAxbVtKv5HdJUcaiOa400uB0X3HMAk5qHxJY3LcttfKAaxXjCpTfx9jXdaUJ8tQsMlf5873IeSjZckREUjQoOeCY+9YhQ9UZILk3Z59Uz7zOASDo9ylPpO8Y0YzBUxeI6nqble60AocCaY38pz2ZSSjVINwtIn12tzNaDJnvSJsn1wfEF14r1Y3Ck72UUHbO9T36y1RQpRsiTe2htnuBtjX+oaic"
				},
				{
					"name": "42-44",
					"origName": "S",
					"rank": 546324,
					"optionId": 1903068411,
					"stocks": []
				},
				{
					"name": "40-42",
					"origName": "XS",
					"rank": 493536,
					"optionId": 1903068412,
					"stocks": []
				}
			],
			"totalQuantity": 1,
			"cardFlags": 2,
			"time1": 8,
			"time2": 100,
			"wh": 6269589634,
			"dtype": 6614249635848,
			"ndtype": 197124,
			"dist": 4048
		}
	]
}
```

# Запрос удаления пункта выдачи заказа

## Request URL
https://user-data-syncer.wb.ru/addresses-syncer/api/v1/addresses/sync?ts=1789894712&device_id=site_0fb3379659fb4d29852eb5085444660c
## Request Method
POST
## Path
/addresses-syncer/api/v1/addresses/sync
## Response Status
200 OK
## Content-Type
application/json
## Response
```JSON
{
	"state": 0,
	"error": "",
	"change_ts": 1789894761,
	"addresses": [],
	"sdp": [
		{
			"id": 307722,
			"type": 0,
			"is_primary": false,
			"client_ts": 1789894699,
			"is_deleted": true,
			"ts": 1789894713
		},
		{
			"id": 146754,
			"type": 0,
			"is_primary": false,
			"client_ts": 1777223219,
			"is_deleted": true,
			"ts": 1789894761
		}
	]
}
```

# Запрос удаления товара, добавленного в корзину

## Request URL
https://www.wildberries.ru/__internal/cart-storage-api/api/basket/sync?ts=1789895111665&device_id=site_0fb3379659fb4d29852eb5085444660c
## Request Method
POST
## Path
/__internal/cart-storage-api/api/basket/sync
## Response Status
200 OK
## Content-Type
application/json
## Response
```JSON
{
	"state": 0,
	"result_set": [],
	"change_ts": 1789895138615
}
```
