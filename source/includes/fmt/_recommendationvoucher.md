## Recommendation Voucher List

> Request Recommendation Voucher List

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/customerrecomendation/rm885j`

**Parameter Recommendation Voucher List**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Recommendation Voucher List

```json
{
  "response_code": 200,
  "status": "ok",
  "data": [
    {
      "voucherId": "1",
      "categoryId": "1",
      "voucherName": "test 1",
      "voucherPrice": "10000",
      "voucherPoint": "10",
      "discount": "0",
      "finalPrice": "10",
      "voucherCode": "",
      "expiredDate": "20200731",
      "voucherImage": "https://storage.googleapis.com/www.dev.pointkita.com/recomendation/soursally.jpg"
    },
    {
      "voucherId": "1",
      "categoryId": "1",
      "voucherName": "test 1",
      "voucherPrice": "10000",
      "voucherPoint": "10",
      "discount": "0",
      "finalPrice": "10",
      "voucherCode": "",
      "expiredDate": "20200731",
      "voucherImage": "https://storage.googleapis.com/www.dev.pointkita.com/recomendation/tsel.jpg"
    }
  ]
}
```

**Parameter Response Recommendation Voucher List**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 