### Generate Token

> Request generate token

```json
{   
    "clientId": "rm885j",
    "codeChallenge": "xxUye",
    "msisdn": "0889654604068",
    "password": "xcode734"
}
```

URL : `POST https://api.dev.pointkita.com/loginauth`

**Request Parameters**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId| string |
codeChallenge| string |
msisdn| No Hp |
password| String | 

> Response generate token

```json
{   
    "clientId": "rm885j",
    "codeChallenge": "xxUye",
    "msisdn": "0889654604068",
    "password": "xcode734"
}
```

**Response Parameters**

Parameter | Nilai | Deskripsi
----------|-------|-----------
clientId| string |
codeChallenge| string |
msisdn| No Hp |
password| String | 

### Login proses

> Request Login

```json
{   
    "authorizationCode" : "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjbGllbnRfaWQiOiJybTg4NWoiLCJtc2lzZG4iOiIwODg5NjU0NjA0MDY4IiwiY29kZV9jaGFsbGVuZ2UiOiJ4eFV5ZSIsImlhdCI6MTU5MzY2NTE0MywiZXhwIjoxNTkzNjc1OTQzfQ.K5eCoTM4sr7fZvC7elfaiRZ4qdlGEotXtaZ58rG5UZs",
    "codeVerifier": "xxUye",
    "clientId": "rm885j",
    "grantType": "auth_code"
}
```
