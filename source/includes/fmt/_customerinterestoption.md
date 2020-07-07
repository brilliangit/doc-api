## Customer Preference Interest

> Request Customer Preference Interest

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/customerinterest/rm885j`

**Parameter Customer Preference Interest**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Customer Preference Interest

```json
{
  "responseCode": 200,
  "status": "ok",
  "data": [
    {
      "interest_id": 1,
      "interest_name": "Coffee",
      "images": "https://storage.googleapis.com/www.dev.pointkita.com//interest/interest/coffee.svg",
      "status": 1
    },
    {
      "interest_id": 3,
      "interest_name": "Groceries",
      "images": "https://storage.googleapis.com/www.dev.pointkita.com//interest/interest/grocery.svg",
      "status": 1
    }
  ]
}
```

**Parameter Response Customer Preference Interest**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 