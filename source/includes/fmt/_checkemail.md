## Check Existing Email

> Request Check Existing Email

```json
{
}
```

URL: `GET https://api.dev.pointkita.com/checkemail?email=darrennubox@gmail.com`

**Parameter Check Existing Email**

Parameter | Nilai | Deskripsi
----------|-------|-----------
email | string | user email

> Response Check Existing Email

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
  "message": "Email yang kamu masukkan belum terdaftar"
}
```

**Parameter Response Check Existing Email**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 