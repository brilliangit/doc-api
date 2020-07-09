## Recommendation Voucher Detail

> Request Recommendation Voucher Detail

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/customerrecomendationdetail/rm885j?adsId=1`

**Parameter Recommendation Voucher Detail**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j
adsId | string | Advertisement Id

> Response Recommendation Voucher Detail

```json
{
  "response_code": 200,
  "status": "ok",
  "data": [
    {
      "voucherId": "TA-1-1",
      "voucherName": "test 1",
      "voucherPrice": "10000",
      "voucherPoint": "10",
      "discount": "0",
      "finalPrice": "10",
      "voucherCode": "",
      "expiredDate": "20200731",
      "voucherImage": "https://storage.googleapis.com/www.dev.pointkita.com/recomendation/soursally.jpg"
    }
  ]
}
```

**Parameter Response Recommendation Voucher Detail**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 