## Login

### Generate Token

> Request generate token

```json
{   
    "clientId": "rm885j",
    "codeChallenge": "xxUye",
    "msisdn": "081XXXXXXXX",
    "password": "xcode734"
}
```

URL : `POST https://api.dev.pointkita.com/loginauth`

**Response Parameters**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId| string |
codeChallenge| string |
msisdn| No Hp |
password| String | 

> Response generate token

```json
{
    "responseCode": 200,
    "status": "ok",
    "data": {
        "authorizationCode": "TOKEN_FROM_BACKEND",
        "expiresIn": "10800"
    }
}
```
**Request Parameters**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
msisdn| No Hp |
data| Object | 



