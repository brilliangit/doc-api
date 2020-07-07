## Login

### Generate Auth Token

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

### Generate Token

> Request generate token

```json
{   
    "authorizationCode" : "TOKEN_FROM_BACKEND",
    "codeVerifier": "xxUye",
    "clientId": "rm885j",
    "grantType": "auth_code"
}
```

URL : `POST https://api.dev.pointkita.com/logintoken`

**Response Parameters**

Parameter | Nilai | Deskripsi
----------|-------|-----------
authorizationCode| string |
codeVerifier| string |
clientId| string |
grantType| string | 

> Response generate token

```json
{
  "responseCode": 200,
  "status": "ok",
  "data": {
    "accessToken": "ACCESS_TOKEN_FROM_BACKEND",
    "refreshToken": "REFRESH_TOKEN_FROM_BACKEND",
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



