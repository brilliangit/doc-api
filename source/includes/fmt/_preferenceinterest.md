## Preference Interest List

> Request Preference Interest List

```json
headers = 
{
    "Content-Type": "application/json",
    "Authorization": "token.user.accessToken"
}
```

URL: `GET https://api.dev.pointkita.com/interest/rm885j`

**Parameter Preference Interest List**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId | string | rm885j

> Response Preference Interest List

```json
{
  "response_code": 200,
  "status": "ok",
  "message": "Success Get Interest Data",
  "data": [
    {
      "interestId": 1,
      "interestName": "Coffee",
      "interestImage": "https://storage.googleapis.com/www.dev.pointkita.com/interest/coffee.svg"
    },
    {
      "interestId": 2,
      "interestName": "Telco Product",
      "interestImage": "https://storage.googleapis.com/www.dev.pointkita.com/interest/telco.svg"
    },
    {
      "interestId": 3,
      "interestName": "Groceries",
      "interestImage": "https://storage.googleapis.com/www.dev.pointkita.com/interest/grocery.svg"
    },
    {
      "interestId": 4,
      "interestName": "Fashion",
      "interestImage": "https://storage.googleapis.com/www.dev.pointkita.com/interest/fashion.svg"
    },
    {
      "interestId": 5,
      "interestName": "Steak",
      "interestImage": "https://storage.googleapis.com/www.dev.pointkita.com/interest/steak.svg"
    }
  ]
}
```

**Parameter Response Preference Interest List**

Parameter | Nilai | Deskripsi
----------|-------|-----------
response_code| string |
status| string |
message| string | 
data| Object | 