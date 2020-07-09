## Earn Partner Detail

> Request Earn Partner Detail

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/partnerdetail/rm885j?partnerId=4&partnerType=1`

**Parameter Earn Partner Detail**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j
partnerId | string | rm885j
partnerType | string | 1: for partner; 2: wallet

> Response Earn Partner Detail

```json
{
  "responseCode": 200,
  "status": "ok",
  "message": "Success get partner detail",
  "data": [
    {
      "partnerId": 4,
      "partnerName": "HappyFresh",
      "partnerImage": "https://storage.googleapis.com/www.dev.pointkita.com/partner/happyfresh.png",
      "color": "#ececec",
      "categoryId": 2,
      "type": 1,
      "partnerUrl": "https://www.happyfresh.id"
    }
  ]
}
```

**Parameter Response Earn Partner Detail**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 