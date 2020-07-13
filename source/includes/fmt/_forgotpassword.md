## Forgot Password Submit

> Request Forgot Password Submit

```json
{
    "msisdn": "081357965616",
    "newPassword": "Xcode734",
    "otpCode": "463261",
	"otpRequestId": "v33y3y"
}
```

URL: `POST https://api.dev.pointkita.com/updatepassword`

**Parameter Forgot Password Submit**

Parameter | Nilai | Deskripsi
----------|-------|-----------
msisdn | string | 
newPassword | string | 
otpCode | string | 
otpRequestId | string | 


> Response Forgot Password Submit

```json
{
    "responseCode": 200,
    "status": "ok",
    "message": ""
}
{
    "responseCode": "201",
    "status": "error",
    "message": "Forgot failed"
}
```

**Parameter Response Forgot Password Submit**

Parameter | Nilai | Deskripsi
----------|-------|-----------
responseCode| string |
status| string |
message| string | 
data| Object | 