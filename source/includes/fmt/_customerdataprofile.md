## Customer Data Profile

> Request Customer Data Profile

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/customerdetail/rm885j`

**Parameter Customer Data Profile**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Customer Data Profile

```json
{
  "responseCode": 200,
  "status": "ok",
  "data": {
    "customer_id": 10,
    "msisdn": "08123456789",
    "name": "Junior AD",
    "dob": "1990-1-5",
    "gender": "0",
    "email": "anindika27@gmail.com",
    "customerTier": {
      "customer_id": 10,
      "card_type": "silver",
      "card_image": "http://"
    },
    "customerPoin": {
      "total_point": 120,
      "detail_point": [
        {
          "name": "pointku",
          "point": 80,
          "expired_date": "2020-11-02",
          "message": "ditukar jadi"
        },
        {
          "name": "bni point",
          "point": 20,
          "expired_date": "2020-11-02",
          "message": "ditukar jadi"
        },
        {
          "name": "telkomsel point",
          "point": 10,
          "expired_date": "2020-11-02",
          "message": "ditukar jadi"
        },
        {
          "name": "linkaja",
          "point": 10,
          "expired_date": "2020-11-02",
          "message": "ditukar jadi"
        }
      ]
    }
  }
}
```

**Parameter Response Customer Data Profile**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 