## Earn Partner List

> Request Earn Partner List

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/partnerearn/rm885j`

**Parameter Earn Partner List**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Earn Partner List

```json
{
  "response_code": 200,
  "status": "ok",
  "message": "Success get partner earning",
  "data": [
    {
      "partnerId": 267,
      "partnerName": "Happy Fresh",
      "partnerImage": "https://s3.amazonaws.com/distributor_image/image-20200611114208.jpg",
      "partnerAddress": "Your Address",
      "partnerTags": [
        "promotion",
        "hot"
      ],
      "partnerType": 3
    }
  ]
}
```

**Parameter Response Earn Partner List**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 