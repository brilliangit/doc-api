## Burn Category Voucher

> Request Burn Category Voucher

```json
headers = {
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/category/clientId`

**Parameter Burn Category Voucher**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Burn Category Voucher

```json
{
  "response_code": 200,
  "status": "ok",
  "message": "Success Get Category Data",
  "data": [
    {
      "categoryId": 1,
      "categoryName": "Food & Beverages",
      "categoryImage": "https://storage.googleapis.com/www.dev.pointkita.com/interest/friedrice.svg"
    },
    {
      "categoryId": 2,
      "categoryName": "Daily Needs",
      "categoryImage": "https://storage.googleapis.com/www.dev.pointkita.com/interest/grocery.svg"
    },
    {
      "categoryId": 3,
      "categoryName": "Telco & Entertainment",
      "categoryImage": "https://storage.googleapis.com/www.dev.pointkita.com/interest/telco.svg"
    },
    {
      "categoryId": 4,
      "categoryName": "Others",
      "categoryImage": "https://storage.googleapis.com/www.dev.pointkita.com/interest/glasses.svg"
    }
  ]
}

```

**Parameter Response Burn Category Voucher**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 