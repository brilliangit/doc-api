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
        "isVerify": true
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