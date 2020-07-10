## Customer Point Details

> Request Customer Point Details

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/customerpoin/rm885j`

**Parameter Customer Point Details**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Customer Point Details

```json
{
    "responseCode": 200,
    "status": "ok",
    "data": {
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
```

**Parameter Response Customer Point Details**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 