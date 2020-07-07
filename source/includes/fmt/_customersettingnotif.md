## Customer Notification Setting 

> Request Customer Notification Setting 

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/customersetting/rm885j`

**Parameter Customer Notification Setting **

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Customer Notification Setting 

```json
{
  "responseCode": 200,
  "status": "ok",
  "data": {
    "customer_id": 10,
    "notifStatus": 1
  }
}
```

**Parameter Response Customer Notification Setting **

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 