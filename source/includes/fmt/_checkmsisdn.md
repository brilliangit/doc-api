## Check Existing MSISDN

> Request Check Existing MSISDN

```json
{
}
```

URL: `GET https://api.dev.pointkita.com/checkmsisdn?msisdn=082112079100`

**Parameter Check Existing MSISDN**

Parameter | Nilai | Deskripsi
----------|-------|-----------
msisdn | number | user phone number

> Response Check Existing MSISDN

```json
{
  "responseCode": 200,
  "status": "ok",
  "data": {
    "customer_id": 19,
    "msisdn": "082112079100",
    "name": "Darren1",
    "dob": "2021-8-18",
    "gender": "1",
    "email": "darrennubox@gmail.com",
    "email_verify": "0",
    "customerTier": {
      "customer_id": 19,
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

{
  "responseCode": "202",
  "status": "error",
  "message": "Nomor yang kamu masukkan belum terdaftar"
}
```

**Parameter Response Check Existing MSISDN**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 