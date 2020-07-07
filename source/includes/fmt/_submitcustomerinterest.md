## Submit Customer Preference

> Request Submit Customer Preference

```json 
{
    "clientId": "rm885j",
    "interestIds" : [{
            "interestId": 1
        },
        {
            "interestId": 3
        }]
}
```

URL: `POST https://api.dev.pointkita.com/customerinterest`

**Parameter Submit Customer Preference**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j
interestIds | object array | 

> Response Submit Customer Preference

```json
{
  "responseCode": 200,
  "status": "ok",
  "message": "Update Customer Interest successfully"
}
```

**Parameter Response Submit Customer Preference**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 