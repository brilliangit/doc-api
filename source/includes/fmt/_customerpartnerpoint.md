## Customer Partner Point

> Request Customer Partner Point

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/customerpartnerpoin/rm885j`

**Parameter Customer Partner Point**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Customer Partner Point

```json
{
    "responseCode": 200,
    "status": "ok",
    "message": "Success get customer partner point",
    "data": [
        {
            "partnerId": 1,
            "partnerName": "MyTelkomsel",
            "partnerImage": "https://storage.googleapis.com/www.dev.pointkita.com/partner/telkomsel.png",
            "partnerPoin": 1000
        },
        {
            "partnerId": 2,
            "partnerName": "BNI",
            "partnerImage": "https://storage.googleapis.com/www.dev.pointkita.com/partner/BNI.png",
            "partnerPoin": 2000
        },
        {
            "partnerId": 3,
            "partnerName": "LinkAja",
            "partnerImage": "https://storage.googleapis.com/www.dev.pointkita.com/partner/link-aja.png",
            "partnerPoin": 500
        }
    ]
}
```

**Parameter Response Customer Partner Point**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 